---
title: "Contact"
date: 2023-12-18T18:20:23+07:00
draft: false
description: This my next awesome post about stuff that my audience love to read.
featured_image: ../assets/images/defaults/featured_image.jpg
---

# {{< i18n "Contact.Title" >}}

<form action="https://formspree.io/f/mkndnwnp" method="POST" class="">
  <div class="">
    <div class="grid grid-cols-1 gap-x-8 gap-y-6 sm:grid-cols-3">
      <div class="sm:col-span-1">
        <label for="name" class="block text-sm font-semibold leading-6 text-white">{{< i18n "Contact.Name" >}}</label>
        <div class="mt-2.5">
          <input type="hidden" name="_language" value="zh-cn">
          <input type="text" name="Name" id="Name" autocomplete="Name" class="block w-full rounded-md border-0 bg-white/5 px-3.5 py-2 text-white shadow-sm ring-1 ring-inset ring-white/10 focus:ring-2 focus:ring-inset focus:ring-indigo-500 sm:text-sm sm:leading-6">
        </div>
      </div>
      <div class="sm:col-span-1">
        <label for="Email" class="block text-sm font-semibold leading-6 text-white">{{< i18n "Contact.Email" >}}</label>
        <div class="mt-2.5">
          <input type="Email" name="Email" id="Email" autocomplete="Email" class="block w-full rounded-md border-0 bg-white/5 px-3.5 py-2 text-white shadow-sm ring-1 ring-inset ring-white/10 focus:ring-2 focus:ring-inset focus:ring-indigo-500 sm:text-sm sm:leading-6">
        </div>
      </div>
      <div class="sm:col-span-1">
        <label for="Phone number" class="block text-sm font-semibold leading-6 text-white">{{< i18n "Contact.PhoneNumber" >}}</label>
        <div class="mt-2.5">
          <input type="tel" name="Phone number" id="Phone number" autocomplete="tel" class="block w-full rounded-md border-0 bg-white/5 px-3.5 py-2 text-white shadow-sm ring-1 ring-inset ring-white/10 focus:ring-2 focus:ring-inset focus:ring-indigo-500 sm:text-sm sm:leading-6">
        </div>
      </div>
      <div class="sm:col-span-3">
        <label for="Message" class="block text-sm font-semibold leading-6 text-white">{{< i18n "Contact.Message" >}}</label>
        <div class="mt-2.5">
          <textarea name="Message" id="Message" rows="4" class="block w-full rounded-md border-0 bg-white/5 px-3.5 py-2 text-white shadow-sm ring-1 ring-inset ring-white/10 focus:ring-2 focus:ring-inset focus:ring-indigo-500 sm:text-sm sm:leading-6"></textarea>
        </div>
      </div>
    </div>
    <div class="mt-8 flex justify-end grid grid-cols-1 gap-x-8 gap-y-6 sm:grid-cols-2">
      <button type="submit" class="sm:col-span-2 rounded-md bg-indigo-500 px-3.5 py-2.5 text-center text-sm font-semibold text-white shadow-sm hover:bg-indigo-400 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-500">{{< i18n "Contact.Send" >}}</button>
    </div>
  </div>
</form>
