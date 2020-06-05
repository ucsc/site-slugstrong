---
layout: page
title: "Your comments"
description: >
  Submit your thoughts and feedback.
menu: "Comments"
sidebar: true
left_col: true
order: 7
front: 
  bg: "#13a5dc"
  color: "#fff"
  icon: "speech-bubble-6.svg"
---

<form class="pa2 black-80" name="comments" method="POST" data-netlify="true">
  <div class="pa2">
    <label for="name" class="f5 db mb2 navy">Your name</label>
    <input type="text" id="name" name="name" />
  </div>
  <div class="pa2">
    <label for="email" class="f5 db mb2 navy">Your email</label>
    <input type="email" id="email" name="email" />
  </div>
    <div class="pa2">
    <label for="phone" class="f5 db mb2 navy">Your phone number</label>
    <input type="phone" id="phone" name="phone" />
  </div>
  <div class="pa2">
    <label for="affiliation">Your affiliation to campus:
      <select name="affiliation" id="affiliation">
        <option value="undergraduate">Undergraduate student</option>
        <option value="graduate">Graduate student</option>
        <option value="faculty-staff">Faculty or staff</option>
        <option value="parent">Parent</option>
        <option value="alumni">Alumni</option>
        <option value="community">Community member</option>
      </select>
    </label>
  </div>
  <div class="pa2">
  <label for="comment" class="f5 db mb2 navy">Comments</label>
    <textarea id="comment" name="comment" class="db border-box hover-black w-100 measure h4 ba b--black-20 pa2 br2 mb2"></textarea>
  </div>
  <div class="pa2">
    <button class="f5 br3 link dim ph3 pv3 mb2 dib white bg-dark-blue" type="submit">Send your comments</button>
  </div>
</form>
