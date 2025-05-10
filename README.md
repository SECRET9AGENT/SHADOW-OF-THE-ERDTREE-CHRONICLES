# SHADOW-OF-THE-ERD-CHRONICLES
[Html.txt](https://github.com/user-attachments/files/20140007/Html.txt)
[Uploading Script.js…]()// Smooth scrolling for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});

// Dynamic header shadow on scroll
window.addEventListener('scroll', () => {
    const nav = document.querySelector('nav');
    if (window.scrollY > 50) {
        nav.style.boxShadow = '0 4px 12px rgba(0, 0, 0, 0.3)';
    } else {
        nav.style.boxShadow = 'none';
    }
});

// Placeholder for future interactive elements
console.log("Shadow of the Erdtree Chronicles - Website Loaded");
[Style.css.txt](https://github.com/user-attachments/files/20140009/Style.css.txt)
