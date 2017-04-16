---
layout: page
title: Kittens
permalink: /netlify/kittens/
---

This page should redirect you to a Google search of Kittens!

<?php
header("HTTP/1.1 301 Moved Permanently");
header("Location: https://www.google.com/search?q=kittens");
exit();
?> 
