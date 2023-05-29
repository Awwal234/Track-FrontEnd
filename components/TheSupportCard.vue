<template>
    <div class="mt-[101px] w-full">
        <div class="flex w-full">
            <div class="w-[35%] px-[54px] pb-[85px]">
                <div class="w-fit mx-auto"><img src="/image/headphones.svg" class="" alt=""/></div>
                <div class="mt-[42px] text-[#000] text-[21px] leading-[28px] font-[500] text-center mx-auto">Support</div>
                <div class="mt-[22px] text-center mx-auto">
                    Centralize your data from multiple sources and process it in real
                    time.
                </div>
            </div>
            <div class="w-[35%] borderLR px-[54px] pb-[85px]">
                <div class="w-fit mx-auto"><img src="/image/chartbar.svg" class="" alt=""/></div>
                <div class="mt-[42px] text-[#000] text-[21px] leading-[28px] font-[500] text-center mx-auto">24/7</div>
                <div class="mt-[22px] text-center mx-auto">
                    Real time feedback for all your queries
                </div>
            </div>
            <div class="w-[35%] px-[54px] pb-[85px]">
                <div class="w-fit mx-auto"><img src="/image/board.svg" class="" alt=""/></div>
                <div class="mt-[42px] text-[#000] text-[21px] leading-[28px] font-[500] text-center mx-auto">Interface</div>
                <div class="mt-[22px] text-center mx-auto">
                    Auto backup, smooth interface ensures you complete your
                    scheduled tasks
                </div>
            </div>
        </div>
        <!--second flex-->
        <div class="flex w-full">
            <div class="w-[35%] borderTP pt-[59px] px-[54px] pb-[85px]">
                <div class="w-fit mx-auto"><img src="/image/backup.svg" class="" alt=""/></div>
                <div class="mt-[42px] text-[#000] text-[21px] leading-[28px] font-[500] text-center mx-auto">Backup</div>
                <div class="mt-[22px] text-center mx-auto">
                    Ensure no data is lost with our auto AI powered backup systems
                </div>
            </div>
            <div class="w-[35%] borderLRP pt-[59px] px-[54px] pb-[85px]">
                <div class="w-fit mx-auto"><img src="/image/flexible.svg" class="" alt=""/></div>
                <div class="mt-[42px] text-[#000] text-[21px] leading-[28px] font-[500] text-center mx-auto">Flexibility</div>
                <div class="mt-[22px] text-center mx-auto">
                    Track&apos;s world class interface built for speed and delight
                </div>
            </div>
            <div class="w-[35%] borderTP pt-[59px] px-[54px] pb-[85px]">
                <div class="w-fit mx-auto"><img src="/image/storage.svg" class="" alt=""/></div>
                <div class="mt-[42px] text-[#000] text-[21px] leading-[28px] font-[500] text-center mx-auto">Storage</div>
                <div class="mt-[22px] text-center mx-auto">
                    Unlimited storage for your teams
                </div>
            </div>
        </div>
        <!--end second flex-->
        <!--team section-->
        <div class="mt-[202px] w-full">
            <div class="font-[400] w-[70%] text-[#000] text-center mx-auto text-[24px] leading-[36px]">
                Your favorite project management team now flexible enough to take on any project. 
                Work how you want and where you want.
            </div>
            <div class="w-fit h-fit mt-[69px]"><img src="/image/teamImage.png" class="w-full" alt=""/></div>
        </div>
        <!--end team section-->
        <PricingSection/>
    </div>
</template>

<style scoped>
.borderLR{
    border-left: 1px solid rgba(167, 161, 161, 0.48);
    border-right: 1px solid rgba(167, 161, 161, 0.48);
}
.borderTP{
    border-top: 1px solid rgba(167, 161, 161, 0.48);
}
.borderLRP{
    border-left: 1px solid rgba(167, 161, 161, 0.48);
    border-top: 1px solid rgba(167, 161, 161, 0.48);
    border-right: 1px solid rgba(167, 161, 161, 0.48);
}
</style>