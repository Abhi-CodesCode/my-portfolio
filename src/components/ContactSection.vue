<template >
    <section class=" text-white mt-20" id="contact">
        <h2 class="text-4xl font-bold text-white text-left mb-4 px-4 xl:pl-16">Let's Connect</h2>
        <div class=" grid grid-cols-2 gap-8 relative px-4 xl:px-16 mt-8" data-aos="zoom-in-up">
            <div>
                <p class="text-[#adb7be] mb-8">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempore rem accusantium consectetur, incidunt molestias eveniet aspernatur minima, earum ratione aperiam nobis ab eum quam. Alias dignissimos magni molestiae explicabo quaerat!</p>
                <div style="background: #111a3e;width: 100%; height: 80%; border-radius: 20px;overflow: hidden; border: 1px solid#111a3e; backdrop-filter: blur(9px);-webkit-backdrop-filter: blur(9px);">
                    
                    <form class="flex flex-col p-2 mx-6 my-4" data-aos="zoom-in-up">
                        <div class="mb-4">
                            <label for="email" class="text-white block mb-2 text-sm font-medium">Email</label>
                            <input type="email" id="email" class="bg-[#111827] placeholder:[#9ca2a9] text-gray-100 text-sm rounded-lg block w-full p-2.5" placeholder="email@email.com" name="email">
                        </div>
                        <div class="mb-6">
                            <label for="subject" class="text-white block mb-2 text-sm font-medium">Subject</label>
                            <input type="subject" id="subject" class="bg-[#111827] placeholder:[#9ca2a9] text-gray-100 text-sm rounded-lg block w-full p-2.5" placeholder="subject" name="subject">
                        </div>
                        <div class="mb-6">
                            <label for="message" class="text-white block mb-2 text-sm font-medium">message</label>
                            <textarea type="message" id="message" class="bg-[#111827] placeholder:[#9ca2a9] text-gray-100 text-sm rounded-lg block w-full p-2.5" placeholder="Let's talk about..." name="message" style="height: 80px;"></textarea>
                        </div>
                        <div class=" flex justify-center">
                            <button class=" z-1 w-[90%!important] px-6 md:px-7 py-3 rounded-full sm:w-max flex justify-center text-white bg-primary">Send message</button>
                        </div>
                    </form>
                </div>
            </div>
            <div class="col-lg-4 col-md-4 mb-lg-4 mt-5">
                <div class="flex mb-10 items-center">
                    <div class="p-2" style="background: #111a3e; width: 50; height: 46; display: flex; justify-content: center; border-radius: 50%; overflow: hidden;
                    border: 1px solid#111a3e; backdrop-filter: blur(9px);-webkit-backdrop-filter: blur(9px);">
                    <img src="https://img.icons8.com/?size=100&id=124430&format=png&color=ffffff" alt="mail-icon" class="w-6">
                </div>
                <div class="ml-5 text-white">
                    <h4>Email</h4>
                    <p>abhi.codescode@gmail.com</p>
                </div>
                </div>
                <div class="flex mb-10 items-center">
                    <div class="p-2" style="background: #111a3e; width: 50; height: 46; display: flex; justify-content: center; border-radius: 50%; overflow: hidden;
                    border: 1px solid#111a3e; backdrop-filter: blur(9px);-webkit-backdrop-filter: blur(9px);">
                    <img src="https://img.icons8.com/?size=100&id=9730&format=png&color=ffffff" alt="call-icon" class="w-6">
                </div>
                <div class="ml-5 text-white">
                    <h4>Phone</h4>
                    <p>+91 89488-02660</p>
                </div>
                </div>
                <div class="flex mb-10 items-center">
                    <div class="p-2" style="background: #111a3e; width: 50; height: 46; display: flex; justify-content: center; border-radius: 50%; overflow: hidden;
                    border: 1px solid#111a3e; backdrop-filter: blur(9px);-webkit-backdrop-filter: blur(9px);">
                    <img src="https://img.icons8.com/?size=100&id=8808&format=png&color=ffffff" alt="linkedIn-icon" class="w-6">
                </div>
                <div class="ml-5 text-white">
                    <h4>LinkedIn</h4>
                    <p>www.linkedin.com/in/abhijeet-k</p>
                </div>
                </div>

            </div>
        </div>
    </section>
</template>
<script setup>

</script>
