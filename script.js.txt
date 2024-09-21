document.getElementById('contact-form').addEventListener('submit', function(e) {
    e.preventDefault(); // Prevent the default form submission
    alert('Thank you for your message! I will get back to you soon.');
    this.reset(); // Reset the form
});
