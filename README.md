# Rust Genetics Calculator

<div class="collapse" id="howtouse">
                    Using the calculator is easy. Enter your crop genes in the text box below as a string of letters
                    (eg. if your crops has <span class="good gene">Y</span>
                                           <span class="good gene">G</span>
                                           <span class="good gene">H</span>
                                           <span class="bad gene">W</span>
                                           <span class="bad gene">X</span>
                                           <span class="good gene">G</span> genes, you would enter YGHWXG) and press enter.
                    The calculator will automatically find the best possible combination of the current entered crops. <br><br>
                    If you want you could also change the preference of what genes you would like to get. Default priorities
                    are set for temperate biomes, so if you live in a cold biome, make sure to increase <span class="good gene">H</span> priority.
                    Click here if you would like to learn more about <a href="#genes">genes</a> or <a href="#crossbreeding">crossbreeding</a>. <br><br>
                    The result of the calculation will apear next to where you entered your crops. It will display what crops you need to crossbreed
                    and what you will get. If you see results with <span class="good gene">?</span> genes, it means that no crossbreeding will occur for
                    that gene.
                </div>
                
<div class="row">
            <div class="col-md-10 offset-md-1">
                <hr>
                <h2 id="genes">Genes</h2>
                <p class="lead">
                    Every plant has 6 genes. Currently there are 5 different gene types that a plant can have.
                    Genes alter the plant behaviour depending on the type and amount. The type of the 6 genes can be
                    changed with cross-breeding. The best gene if you are not in the winter biome is any combination of 4
                    <span class="good gene">G</span> and 2 <span class="good gene">Y</span> genes.
                </p>
            </div>
        </div>
<div class="row">
            <div class="col-md-5 offset-md-1 bg-panel p-3">
                <span class="good gene">Y</span> Increases crop <span class="good">production amount</span> <span class="small">(yield)</span> <br>
                <span class="good gene">G</span> Increases crop <span class="good">growth rate</span>  <br>
                <span class="good gene">H</span> Increases crop <span class="good">cold resistance</span>  <br>
            </div>
            <div class="col-md-5 bg-panel p-3">
                <span class="bad gene">W</span> Increases <span class="bad">water usage</span>  <br>
                <span class="bad gene">X</span> Don't do nothing but has priority for crossbreeding
            </div>
        </div>
        <br>
<p>
                    About 20 minutes after planting every crop will enter a crossbreading stage. When it enteres this stage, the plant will look
                    at its <strong>neighbour plants in the planter</strong> (not including itself) for any genes that it can recive.
                    The crossbreading stage will also be indicated when looking at the plant under the stage category.
                </p>
                <p>If you are interesed in a detailed explanation of crossbreeding i sugest watching <a href="https://www.youtube.com/watch?v=WQ0ixceBZwA">this video</a> but in short when crossbreeding occurs, the crop will go looking for each of the six genes of neighbours and
                    select the one that was found the most times for that position (with negative ones taking priority). If all genes
                    had the same amount of occurances, no crossbreading will occur for that gene.</p>
                
                
 This calculator is originaly made by <a href="https://steamcommunity.com/id/LKoos/">LKoos </a> as i cannot make contact with him, i made some improvements.
                My steam is <a href="https://steamcommunity.com/id/birraftw/">Birra</a> © 2020 send me a email if you want! <a href="mailto:cesar.d.moro@gmail.com">cesar.d.moro@gmail.com</a>

Link to source code on https://github.com/cesardmoro/rust-genetics-calculator
