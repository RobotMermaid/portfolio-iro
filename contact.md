---
layout: page
title: Contact
permalink: /contact/
feature-img: "img/AstroSirenTiny.png"
---

If you made it this far into my website, let me know what you think, or if you found any typos, or just to say "hi".

I am currently looking to be hired.  
I cannot at this point relocate but I hope to someday work from Paris or Auckland or Singapore...

<!-- <form >
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <!-- <input type='hidden' name='redirect_to' value='http://robotmermaid.com/thank-you/' />
  <input type='text' name='name' placeholder='Your Full Name' />
  <input type='email' name='email' placeholder='Your E-mail Address' />
  <textarea name='message' placeholder='Write your message ...'></textarea>
  <input type='submit' value='Send Message' /> -->
<!-- </form> --> -->
<form action="https://getsimpleform.com/messages?form_api_token=2244d304b83e7b8dcc6777ed4c32484e" method="post" enctype="multipart/form-data">

  <input type='hidden' name='redirect_to' value='http://robotmermaid.com/thank-you/' />
  <input type='hidden' name='_folder' value='rfps' />
  <input type='hidden' name='_spam' value='message' />


  <div class="form-group">
    <label>Name</label>
    <input type="text" name='name' class="form-control">
  </div>

  <div class="form-group">
    <label>Address</label>
    <textarea name='address' rows=8 class="form-control"></textarea>
  </div>


  <div class="form-group">
    <label>Message</label>
    <textarea type="text" name='message' class="form-control"></textarea>
  </div>



  <div class="checkbox">
    <label>
      <input type="checkbox" name='contact' value='Yes'> Do you want us to contact you?
      <input type='hidden' name='contact' value='No'>
    </label>
  </div>

  <button type='submit' class="btn btn-primary">Submit</button>
</form>
