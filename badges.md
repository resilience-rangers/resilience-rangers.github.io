---
layout: page
title: Badges
description: Achieving Resilience
permalink: /badges/
---

A system of badges provides a fun gamification element to the learning of important skills.

It's expected that everyone picks up Cooperation first. It's your guide for how organization should work with other Resilience Rangers. [Read the requirements for Cooperation](/badges/cooperation) to get a sense of how Resilience Rangers are organized.

<style>
.list-with-icon-caption { font-size: 0.8em; }
.greennature-icon-with-list-item { margin:30px; margin-left: 0px}
</style>

<div class="greennature-item greennature-icon-with-list-item">
  {% for badge in site.data.badges %}
    <div class="list-with-icon-ux greennature-ux" style="opacity: 1; padding-top: 0px; margin-bottom: 0px;">
      <div class="list-with-icon greennature-left">
        <div class="list-with-icon-image">
          <div class="image-cropper" style="background-color: {{badge.background-color}}; width: 50px; height: 50px; position: relative; overflow: hidden; border-radius: 50%; border: thin dashed lightgreen;">
            <a href="/badges/{{badge.slug}}"><img src="/assets/images/{{badge.icon}}" style="display:inline; height: {{badge.height}}; width: auto; margin: {{badge.margin}};" /></a>
          </div>
        </div>
        <div class="list-with-icon-content">
          <a href="/badges/{{badge.slug}}">
            <div class="list-with-icon-title greennature-skin-title">{{badge.name}}</div>
            <div class="list-with-icon-caption">
              <p>{{badge.description}}</p>
            </div>
          </a>
        </div>
        <div class="clear"></div>
      </div>
    </div>
  {% endfor %}
  <div class="clear"></div>
</div>

When obtaining Cooperation, you learn about the four core organizational groups: **Procurement**, **Production**, **Education**, and **Security**. One who considers themselves a Resilience Ranger (as opposed to in-training) should achieve badges that mirror each of those areas. For example a newbie Ranger might take:

<div class="greennature-item greennature-icon-with-list-item">
  <div class="list-with-icon-ux greennature-ux" style="opacity: 1; padding-top: 0px; margin-bottom: 0px;">
    <div class="list-with-icon greennature-left">
      <div class="list-with-icon-image">
        <div class="image-cropper" style="background-color: {{badge.background-color}}; width: 50px; height: 50px; position: relative; overflow: hidden; border-radius: 50%; border: thin dashed lightgreen;">
          <a href="/badges/renewable-energy/"><img src="/assets/images/icon-3.png"  /></a>
        </div>
      </div>
      <div class="list-with-icon-content">
        <div class="list-with-icon-title greennature-skin-title">Renewable Energy</div>
        <div class="list-with-icon-caption">
          (for Procurement)
        </div>
      </div>
      <div class="clear"></div>
    </div>
  </div>
  <div class="list-with-icon-ux greennature-ux" style="opacity: 1; padding-top: 0px; margin-bottom: 0px;">
    <div class="list-with-icon greennature-left">
      <div class="list-with-icon-image">
        <div class="image-cropper" style="background-color: beige; width: 50px; height: 50px; position: relative; overflow: hidden; border-radius: 50%; border: thin dashed lightgreen;">
          <a href="/badges/gardening"><img src="/assets/images/fruit-icon-png-4.png" style="display:inline; height: 70%; width: auto; margin: 8px 0 0 7px;"></a>
        </div>
      </div>
      <div class="list-with-icon-content">
        <div class="list-with-icon-title greennature-skin-title">Gardening</div>
        <div class="list-with-icon-caption">
          (for Production)
        </div>
      </div>
      <div class="clear"></div>
    </div>
  </div>
  <div class="list-with-icon greennature-left">
    <div class="list-with-icon-image">
      <div class="image-cropper" style="background-color: {{badge.background-color}}; width: 50px; height: 50px; position: relative; overflow: hidden; border-radius: 50%; border: thin dashed lightgreen;">
        <a href="/badges/cooperation/"><img src="/assets/images/coop.jpeg"  /></a>
      </div>
    </div>
    <div class="list-with-icon-content">
      <div class="list-with-icon-title greennature-skin-title">Cooperation</div>
      <div class="list-with-icon-caption">
        (for Education)
      </div>
    </div>
    <div class="clear"></div>
  </div>
  <div class="list-with-icon greennature-left">
    <div class="list-with-icon-image">
      <div class="image-cropper" style="background-color: #efeefe; width: 50px; height: 50px; position: relative; overflow: hidden; border-radius: 50%; border: thin dashed lightgreen;">
        <a href="/badges/archery"><img src="/assets/images/bow-and-arrow.jpg" style="display:inline; height: 75%; width: auto; margin: 7px 0 0 1px;"></a>
      </div>
    </div>
    <div class="list-with-icon-content">         
      <div class="list-with-icon-title greennature-skin-title">Archery</div>
      <div class="list-with-icon-caption">
        (or Rifles/Shotguns/Self Defense for Security)
      </div>
    </div>
    <div class="clear"></div>
  </div>
  <div class="clear"></div>
</div>

<p> 
It's important to note that these are just guidelines, as there are no minimum or maximum number of badges to achieve. Ultimately, you should focus what you think is important as an individual or as a group.
</p>

Beta Notice: Badges and their requirements are all in a rough draft stage. The purpose of this page is to solicit discussion, so if you're not seeing something here or you have a good idea please let us know at <a href="mailto:info@resiliencerangers.org">info@resiliencerangers.org</a> or if you're inclined check out our <a href="https://github.com/resilience-rangers/resilience-rangers.github.io">github project</a>.

<br><br><br>

<!--
- Athletics + Personal Fitness
- Smelting and forging
- All - Cooking
- Crime Prevention
- Digital Technology - Programming, Robotics, Radio?
- Empathy - Disabilities Awareness + queer, trans / racial sensitivity, other intersectional endeavors
- Electricity/Electronics - read and recite, how does muni-power work?, do it, lighting, solar, charging of batts, scavenge/salvage
- Emergency Preparedness
- Exploration - natural forage - talk about some natural resources around you, go find it, plan for another area
- Plant Science (Forestry)
- Rifle + shotgun Shooting
- Safety, Search and Rescue
- Sustainability
- Textile - incl. Leatherwork, Pulp and Paper ! diy
- Wilderness Survival
- Welding
- Woodwork
-->
