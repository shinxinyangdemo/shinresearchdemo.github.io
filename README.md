<p>This is the page showcasing some of my research topics' output demos, for my creative works: (<a href="https://shinxinyangdemo.github.io" target="_blank">shinxinyangdemo.github.io</a>)</p>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Research Output Demos</title>
    <!-- Add CSS for Flexbox and Styling -->
    <style>
        .section {
            margin-top: 40px;
        }
        .audio-row {
            display: flex;
            justify-content: space-around;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;  /* Space between elements */
            margin-bottom: 30px;  /* Space after each row */
        }
        .audio-item {
            flex: 1;
            text-align: center;
            min-width: 200px; /* Ensures space allocation for audio clips */
        }
        audio {
            width: 100%;
        }
        .section img {
            width: 80%;
            margin: 20px auto;
            display: block;
        }
    </style>
</head>
<body>

    <!-- First Section: GNN Guided Mashup Generation -->
    <div class="section">
        <h1>Graph Neural Network Guided Music Mashup Generation</h1>
        <p>Developed graph neural networks to model the interactions between vocals and instrumentals as a bipartite matching problem at the 'grains' level (quarter-bar segments). This approach yielded surprising results for music mashups, where the model successfully learned to rearrange and blend original instrumentals with elements from different songs, often creating unexpected yet cohesive fusions. This technique holds great potential across various fields, offering a flexible tool for producers and music enthusiasts as a sound design solution. It allows for novel outcomes that might be fatiguing to achieve manually. This project embodies my future research direction after my thesis—creating innovative tools for sound design that offer fresh perspectives on music production.</p>

<!-- Audio Rows -->
<div class="audio-row">
    <div class="audio-item">
        <h3>Original 1</h3>
        <audio controls>
            <source src="original_1.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
    <div class="audio-item">
        <h3>Original 2</h3>
        <audio controls>
            <source src="original_12.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
    <div class="audio-item">
        <h3>Mashup 1</h3>
        <audio controls>
            <source src="mashup_1.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
</div>

<div class="audio-row">
    <div class="audio-item">
        <h3>Original 2</h3>
        <audio controls>
            <source src="original_2.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
    <div class="audio-item">
        <h3>Original 2</h3>
        <audio controls>
            <source src="original_22.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
    <div class="audio-item">
        <h3>Mashup 2</h3>
        <audio controls>
            <source src="mashup_2.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
</div>

<div class="audio-row">
    <div class="audio-item">
        <h3>Original 3</h3>
        <audio controls>
            <source src="original_3.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
    <div class="audio-item">
        <h3>Original 2</h3>
        <audio controls>
            <source src="original_32.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
    <div class="audio-item">
        <h3>Mashup 3</h3>
        <audio controls>
            <source src="mashup_3.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
</div>

<div class="audio-row">
    <div class="audio-item">
        <h3>Original 4</h3>
        <audio controls>
            <source src="original_4.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
    <div class="audio-item">
        <h3>Original 2</h3>
        <audio controls>
            <source src="original_42.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
    <div class="audio-item">
        <h3>Mashup 4</h3>
        <audio controls>
            <source src="mashup_4.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
</div>

<div class="audio-row">
    <div class="audio-item">
        <h3>Original 5</h3>
        <audio controls>
            <source src="original_5.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
    <div class="audio-item">
        <h3>Original 2</h3>
        <audio controls>
            <source src="original_52.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
    <div class="audio-item">
        <h3>Mashup 5</h3>
        <audio controls>
            <source src="mashup_5.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
</div>

<p>Original 1 provides the vocals and instrumentals, original 2 provides the instrumentals, the mashup instrumental is rearranged through the network which is a fusion of both originals</p>


        <!-- Model Overview Image -->
        <img src="gnn_model_overview.jpg" alt="GNN Model Overview" style="width: 100%; height: auto; display: block; margin: 0 auto;">

    </div>

    <!-- Second Section: Diffusion Models for Automatic Music Mixing -->
    <div class="section">
        <h1>Diffusion Models for Automatic Music Mixing</h1>

         <p>Developed diffusion models designed to enhance multi-channel music by simulating an imbalanced mix and progressively improving it through a mixing process. In this task, the signals contributing to the 'bad' mix are treated as noise, which is then incrementally removed to achieve a balanced output. This work can be further developed into a tool for audio enhancing which is also a great tool I believe! Please note that the imbalanced input below may contain significant volume and frequency disparities, so <b>! lowering the volume! </b> before playback is recommended.</p>

        <!-- Audio Rows -->
        <div class="audio-row">
            <div class="audio-item">
                <h3>Imbalanced Input 1</h3>
                <audio controls>
                    <source src="imbalanced_input_1.wav" type="audio/wav">
                    Your browser does not support the audio element.
                </audio>
            </div>
            <div class="audio-item">
                <h3>Diffusion Mix 1</h3>
                <audio controls>
                    <source src="diffusion_mix_1.wav" type="audio/wav">
                    Your browser does not support the audio element.
                </audio>
            </div>
        </div>

        <div class="audio-row">
            <div class="audio-item">
                <h3>Imbalanced Input 2</h3>
                <audio controls>
                    <source src="imbalanced_input_2.wav" type="audio/wav">
                    Your browser does not support the audio element.
                </audio>
            </div>
            <div class="audio-item">
                <h3>Diffusion Mix 2</h3>
                <audio controls>
                    <source src="diffusion_mix_2.wav" type="audio/wav">
                    Your browser does not support the audio element.
                </audio>
            </div>
        </div>

        <div class="audio-row">
            <div class="audio-item">
                <h3>Imbalanced Input 3</h3>
                <audio controls>
                    <source src="imbalanced_input_3.wav" type="audio/wav">
                    Your browser does not support the audio element.
                </audio>
            </div>
            <div class="audio-item">
                <h3>Diffusion Mix 3</h3>
                <audio controls>
                    <source src="diffusion_mix_3.wav" type="audio/wav">
                    Your browser does not support the audio element.
                </audio>
            </div>
        </div>

        <!-- Model Overview Image -->
        <img src="diffusion_model_overview.jpg" alt="Diffusion Model Overview">
    </div>
    
<h1>End</h1>
<p>Thank you for taking the time to explore my research demos! I believe these models are both creative and intuitive for music enthusiasts. Students would find it exciting to build these kinds of models and use them creatively in their own projects.</p>

</body>
</html>
