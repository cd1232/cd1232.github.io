---
layout: home
title: Contact
permalink: /contact/
---

<div class="container mx-auto pb-10">
    <h2 class="text-2xl font-semibold text-center">Contact Me</h2>
    <div class="w-full lg:w-2/3 xl:w-1/2 mx-auto">
        <form
            action="https://formspree.io/xwkrwdeq"
            method="POST" class="p-3">
                <div class="flex flex-col">
                    <div>
                        <label class="sr-only">
                            Your email:                            
                        </label>
                        <input type="text" class="outline-none focus:border-gray-500 w-full my-3 py-2 px-1 border" name="_replyto" placeholder="Email">
                    </div>
                    <div>
                        <label class="sr-only">
                            Your message:                           
                        </label>
                         <textarea class="outline-none focus:border-gray-500 w-full my-3 pt-1 px-1 border" rows="5" name="message" placeholder="Message"></textarea>
                    </div>  
                    <button type="submit" class="self-end bg-blue-700 px-3 py-2 rounded text-white hover:bg-blue-500">Send</button>
                </div>      
        </form>
    </div>
</div>