<template>
    <div class="container h-100">
        <div class="row justify-content-center h-100">
            <div class="col-12 col-md-8 col-lg-6 col-xl-4 my-auto">
                <div class="card mb-3">
                    <div class="card-body">
                        <img src="/images/logo-only.svg" alt="Red meridian logo" width="64" height="64">
                        <h1>Put on your warmest socks and get ready to relax</h1>
                        <p>meridian is the new cosy corner of ASMR - launching soon.</p>
                        <ul>
                            <li>Totally ad-free</li>
                            <li>Higher-quality, uncompressed audio</li>
                            <li>Features designed specifically for ASMR</li>
                            <li>Optional, per-channel subscribers-only content</li>
                        </ul>
                        <p class="mb-4">Want to be notified when we launch?</p>
                        <div class="text-end">
                            <a href="https://docs.google.com/forms/d/e/1FAIpQLScgGThtnfLNFMPvt6iCx0Of6OhiWTZRUFug3nZzM2U6WrwKCg/viewform?usp=sf_link" target="_blank" class="btn btn-lg btn-outline-primary">
                                Register your interest
                            </a>
                        </div>
                    </div>
                </div>
                <div class="row mt-1">
                    <div class="col-6 text-start">
                        <p class="text-muted small col-form-label">&copy; 2023</p>
                    </div>
                    <div class="col-6 text-end">
<!--                        <a href="https://twitter.com/meridian_stream" target="_blank" class="social">-->
<!--                            <i class="fa-brands fa-twitter"></i>-->
<!--                        </a>-->
                        <a href="https://discord.gg/HuUqd5wHSb" target="_blank" class="social">
                            <i class="fa-brands fa-discord"></i>
                        </a>
<!--                        <a href="https://www.reddit.com/r/meridian_stream" target="_blank" class="social">-->
<!--                            <i class="fa-brands fa-reddit-alien"></i>-->
<!--                        </a>-->
<!--                        <a href="https://www.instagram.com/meridian.stream" target="_blank" class="social">-->
<!--                            <i class="fa-brands fa-instagram"></i>-->
<!--                        </a>-->
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        mounted () {
            console.log(window.location.host)
        }
    }
</script>
