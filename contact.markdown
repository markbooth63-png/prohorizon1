---
layout: default
title: Contact Us
permalink: /contact/
---

<div class="container py-5">
  <h1 class="text-center mb-5">Contact Us</h1>
  
  <div class="row">
    <div class="col-md-6">
      <form id="contactForm" class="needs-validation" novalidate>
        <div class="mb-3">
          <label for="name" class="form-label">Name</label>
          <input type="text" class="form-control" id="name" required>
          <div class="invalid-feedback">
            Please provide your name.
          </div>
        </div>
        
        <div class="mb-3">
          <label for="email" class="form-label">Email</label>
          <input type="email" class="form-control" id="email" required>
          <div class="invalid-feedback">
            Please provide a valid email address.
          </div>
        </div>
        
        <div class="mb-3">
          <label for="subject" class="form-label">Subject</label>
          <input type="text" class="form-control" id="subject" required>
          <div class="invalid-feedback">
            Please provide a subject.
          </div>
        </div>
        
        <div class="mb-3">
          <label for="message" class="form-label">Message</label>
          <textarea class="form-control" id="message" rows="5" required></textarea>
          <div class="invalid-feedback">
            Please enter your message.
          </div>
        </div>
        
        <button type="submit" class="btn btn-primary">Send Message</button>
        <div class="alert alert-success mt-3 d-none" id="submitSuccess">
          Thank you for your message! We'll get back to you soon.
        </div>
      </form>
    </div>
    
    <div class="col-md-6">
      <div class="bg-light p-4 rounded h-100">
        <h3>Get in Touch</h3>
        <p>We'd love to hear from you. Contact us using the form or reach out directly using the information below.</p>
        
        <div class="d-flex align-items-center mb-3">
          <div class="bg-primary rounded-circle p-2 text-white me-3">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-geo-alt" viewBox="0 0 16 16">
              <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"/>
              <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"/>
            </svg>
          </div>
          <div>
            <h5 class="mb-0">Address</h5>
            <p class="mb-0">123 Business Street, Suite 100<br>San Francisco, CA 94107</p>
          </div>
        </div>
        
        <div class="d-flex align-items-center mb-3">
          <div class="bg-primary rounded-circle p-2 text-white me-3">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-envelope" viewBox="0 0 16 16">
              <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4Zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2Zm13 2.383-4.708 2.825L15 11.105V5.383Zm-.034 6.876-5.64-3.471L8 9.583l-1.326-.795-5.64 3.47A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.741ZM1 11.105l4.708-2.897L1 5.383v5.722Z"/>
            </svg>
          </div>
          <div>
            <h5 class="mb-0">Email</h5>
            <p class="mb-0">info@prohorizon.com</p>
          </div>
        </div>
        
        <div class="d-flex align-items-center">
          <div class="bg-primary rounded-circle p-2 text-white me-3">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-telephone" viewBox="0 0 16 16">
              <path d="M3.654 1.328a.678.678 0 0 0-1.015-.063L1.605 2.3c-.483.484-.661 1.169-.45 1.77a17.568 17.568 0 0 0 4.168 6.608 17.569 17.569 0 0 0 6.608 4.168c.601.211 1.286.033 1.77-.45l1.034-1.034a.678.678 0 0 0-.063-1.015l-2.307-1.794a.678.678 0 0 0-.58-.122l-2.19.547a1.745 1.745 0 0 1-1.657-.459L5.482 8.062a1.745 1.745 0 0 1-.46-1.657l.548-2.19a.678.678 0 0 0-.122-.58L3.654 1.328zM1.884.511a1.745 1.745 0 0 1 2.612.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.678.678 0 0 0 .178.643l2.457 2.457a.678.678 0 0 0 .644.178l2.189-.547a1.745 1.745 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.634 18.634 0 0 1-7.01-4.42 18.634 18.634 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877L1.885.511z"/>
            </svg>
          </div>
          <div>
            <h5 class="mb-0">Phone</h5>
            <p class="mb-0">(123) 456-7890</p>
          </div>
        </div>
        
        <h4 class="mt-4">Business Hours</h4>
        <table class="table table-borderless">
          <tbody>
            <tr>
              <td>Monday - Friday</td>
              <td>9:00 AM - 5:00 PM</td>
            </tr>
            <tr>
              <td>Saturday</td>
              <td>10:00 AM - 2:00 PM</td>
            </tr>
            <tr>
              <td>Sunday</td>
              <td>Closed</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const form = document.getElementById('contactForm');
    const successMessage = document.getElementById('submitSuccess');
    
    if (form) {
      form.addEventListener('submit', function(event) {
        event.preventDefault();
        
        if (!form.checkValidity()) {
          event.stopPropagation();
          form.classList.add('was-validated');
        } else {
          // Form is valid, show success message
          successMessage.classList.remove('d-none');
          form.reset();
          form.classList.remove('was-validated');
          
          // Hide success message after 5 seconds
          setTimeout(() => {
            successMessage.classList.add('d-none');
          }, 5000);
        }
      });
    }
  });
</script>
