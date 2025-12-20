---
layout: page
title: Blog
permalink: /blog/
nav: true
nav_order: 4
---

<style>
  /* --- Navigation Bar Consistency --- */
  .navbar {
    padding-top: 20px !important;
    padding-bottom: 20px !important;
  }
  .navbar-nav .nav-item .nav-link {
    font-size: 18px !important;
    font-weight: 500 !important;
    margin-left: 15px !important;
    margin-right: 15px !important;
    color: #4a4a4a !important;
    text-transform: capitalize !important;
  }
  .navbar-nav .nav-item .nav-link:hover {
    color: #007bff !important;
  }
  .navbar-nav .nav-item.active .nav-link {
    color: #007bff !important;
    font-weight: bold !important;
  }

  /* --- Blog Card Styles --- */
  .blog-card {
    background-color: #ffffff;
    border: 2px solid #007bff; /* The Signature Blue Border */
    border-radius: 15px;
    overflow: hidden;
    height: 100%;
    transition: transform 0.2s, box-shadow 0.2s;
    display: flex;
    flex-direction: column;
  }
  
  .blog-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 25px rgba(0, 123, 255, 0.15); /* Blue-ish shadow */
  }

  /* Image Area */
  .blog-img-container {
    height: 180px;
    background-color: #f1f3f5;
    overflow: hidden;
    position: relative;
  }
  .blog-img-container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  /* Content Area */
  .blog-body {
    padding: 20px;
    display: flex;
    flex-direction: column;
    flex-grow: 1;
  }

  /* Category Badge */
  .blog-category {
    background-color: #eaf6ff;
    color: #0056b3;
    font-size: 11px;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 1px;
    padding: 4px 8px;
    border-radius: 4px;
    display: inline-block;
    margin-bottom: 10px;
    width: fit-content;
  }

  /* Title & Date */
  .blog-title {
    font-size: 18px;
    font-weight: 700;
    color: #333;
    margin-bottom: 8px;
    line-height: 1.4;
  }
  .blog-date {
    font-size: 12px;
    color: #999;
    margin-bottom: 12px;
    display: block;
  }

  /* Excerpt Text */
  .blog-text {
    font-size: 14px;
    color: #555;
    line-height: 1.6;
    margin-bottom: 15px;
    flex-grow: 1;
  }

  /* Read More Link */
  .blog-link {
    font-size: 14px;
    font-weight: 600;
    color: #007bff;
    text-decoration: none;
    display: flex;
    align-items: center;
  }
  .blog-link i {
    margin-left: 5px;
    transition: margin-left 0.2s;
  }
  .blog-link:hover i {
    margin-left: 10px; /* Arrow moves on hover */
  }
</style>

<div class="row mb-5">
  <div class="col-12 text-center">
    <h1 style="font-weight: 800; color: #333;">Design & Code</h1>
    <p style="color: #666; font-size: 18px;">Thoughts on Engineering, Automation, and Life.</p>
  </div>
</div>

<div class="row">

  <div class="col-md-4 mb-4">
    <a href="#" style="text-decoration: none;"> <div class="blog-card">
        <div class="blog-img-container">
           <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=600&q=80" alt="Coding">
        </div>
        <div class="blog-body">
          <span class="blog-category">Automation</span>
          <span class="blog-date">Dec 18, 2025</span>
          <h3 class="blog-title">Getting Started with Creo Toolkit</h3>
          <p class="blog-text">
            A beginner's guide to setting up your environment for automating CAD workflows using C++...
          </p>
          <span class="blog-link">Read Article <i class="fas fa-arrow-right"></i></span>
        </div>
      </div>
    </a>
  </div>

  <div class="col-md-4 mb-4">
    <a href="#" style="text-decoration: none;">
      <div class="blog-card">
        <div class="blog-img-container">
           <img src="https://images.unsplash.com/photo-1581094794329-cd1361ddee2d?auto=format&fit=crop&w=600&q=80" alt="Engineering">
        </div>
        <div class="blog-body">
          <span class="blog-category">Engineering</span>
          <span class="blog-date">Nov 10, 2025</span>
          <h3 class="blog-title">Standardizing Transformer Tanks</h3>
          <p class="blog-text">
            How we reduced design errors by 15% through strict GD&T standardization practices...
          </p>
          <span class="blog-link">Read Article <i class="fas fa-arrow-right"></i></span>
        </div>
      </div>
    </a>
  </div>

  <div class="col-md-4 mb-4">
    <a href="#" style="text-decoration: none;">
      <div class="blog-card">
        <div class="blog-img-container">
           <img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=600&q=80" alt="Life">
        </div>
        <div class="blog-body">
          <span class="blog-category">Career</span>
          <span class="blog-date">Oct 05, 2025</span>
          <h3 class="blog-title">Switching from Creo to NX</h3>
          <p class="blog-text">
            My experience transitioning between two major CAD software packages and the challenges faced...
          </p>
          <span class="blog-link">Read Article <i class="fas fa-arrow-right"></i></span>
        </div>
      </div>
    </a>
  </div>

</div>
