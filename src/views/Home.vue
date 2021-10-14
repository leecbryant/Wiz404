<template>
    <div class="container mt-5">
       <div class="row">
            <div class="col">
                <h1>The Problems</h1>
                <p class="subtitle">Why Wizard101Central Isn't Enough</p>
                
                <div class="card purple mt-5">
                    <div class="card-body">
                        <h5 class="card-title">Inaccurate</h5>
                        <p class="card-text">Central has a strict anti-datamining, anti-item-finder policy. All information must come from first-hand observations, sometimes leading to inaccurate and incomplete data.</p>
                    </div>
                </div>
                <div class="card purple mt-4">
                    <div class="card-body">
                        <h5 class="card-title">Outdated</h5>
                        <p class="card-text">Pages are left unfinished months or years after their respective update has released. This is a result of general inactivity, the first-hand observation requirement, and Central’s Test Realm policy. Data input is not allowed until Test Realm goes live.</p>
                    </div>
                </div>
                <div class="card purple mt-4">
                    <div class="card-body">
                        <h5 class="card-title">Cluttered</h5>
                        <p class="card-text">The UI on many entries make it difficult to find what you need.</p>
                    </div>
                </div>
                <div class="card purple mt-4">
                    <div class="card-body">
                        <h5 class="card-title">Unreliable</h5>
                        <p class="card-text">Downtime has become more frequent in recent years. With frequent inactivity from the maintainers, this has become a regular problem.</p>
                    </div>
                </div>
                <div class="card purple mt-4">
                    <div class="card-body">
                        <h5 class="card-title">Unfulfilling</h5>
                        <p class="card-text">There is untapped potential for new ideas that the maintainers of Central have not taken advantage of. Displaying an item’s revision history, trivia, or game models in-browser are just a few ideas for expanding on the Wiki.</p>
                    </div>
                </div>

                <h6 class="no-ill mt-5">
                    Wizard404 has no ill-will towards Central Forums. We appreciate the help Wizard101 and Pirate101 Central has been to the community over the years. 
                    However, we feel there is a lot of room for improvement, and have listed the above examples as reasons for creating our own Wiki. 
                    In fact, we already have two former Central Wikimasters on our team.
                </h6>
            </div>
            <div class="col col-md-offset-2">
                <h1>Our Solution</h1>  
                <p class="subtitle">What we are doing</p>
                <div class="card dark mt-5" style="width: 100%;">
                    <div class="card-body">
                        <p class="card-text">
                            We’re going to fix every problem listed above. The issues with Central’s wiki aren’t rocket science. Most of them come from a stubborn attitude towards change, and a lack of passion from the higher-ups.

                            <br/><br/>

                            We aren’t ready to list all of our plans quite yet. You may be able to discern some of them from the problems listed above. However, our team has already created mockups for a few of our ideas.
                            As we expand our team and Wizard404 begins development, we will start posting updates on our progress right here. After all, a Wiki should be a community effort!
                        </p>
                    </div>
                </div>

                <h1 class='mt-5'>Live Twitter Feed</h1>
                <p class="subtitle">Coming Soon....</p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        setup() {
        }
    }
</script>


<style scoped>
    h1 {
        color: #fff;
    }
    .subtitle {
        color: #be46b0;
        margin-top: -0.75em;
    }
    .card.purple {
        background-color:#8d51ae;
    }
    .card.dark {
        background-color:#2d2d2d;
        border-color: grey;
    }
    .card-title {
        color: #fff;
        font-weight: bold;
    }
    .card-text {
        color: #fff;
    }
    .no-ill {
        color: #fff;
        font-size: 0.75em;
    }
</style>