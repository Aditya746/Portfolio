# Aditya Srivastava - My Personal Portfolio

Modern responsive portfolio built completely with vanilla HTML/CSS/JS featuring GSAP animations, performance optimizations, and accessibility compliance.

## Core Features

- **GSAP Animations**: Scroll-triggered animations, parallax effects, typing animations
- **Performance**: Lazy loading, debounced events, resource preloading, 60fps animations
- **Accessibility**: WCAG 2.1 AA compliant, keyboard navigation, ARIA attributes
- **Responsive**: Mobile-first design with touch-friendly interactions

## Technical Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Animations**: GSAP (GreenSock Animation Platform)
- **Performance**: Intersection Observer API, requestAnimationFrame
- **Accessibility**: Semantic HTML, ARIA labels, focus management

## Architecture

```javascript
class WebsiteEnhancer {
  setupLazyLoading()        // Intersection Observer for images
  setupHamburgerMenu()      // Mobile navigation with keyboard support
  setupSmoothScrolling()    // Native smooth scroll with offset handling
  setupParallaxEffect()     // Mouse-based parallax using requestAnimationFrame
  setupScrollAnimations()   // GSAP ScrollTrigger for viewport animations
  setupTypingEffect()       // Dynamic text animation with cursor
  setupCopyButtons()        // Clipboard API integration
  setupBackToTop()          // Scroll-triggered button with smooth scroll
  setupAccessibility()      // Keyboard navigation, focus management
  setupPerformanceOptimizations() // Debounced events, memory cleanup
}
```

## Performance Metrics

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **FCP**: < 1.5s | **LCP**: < 2.5s | **CLS**: < 0.1
- **Bundle Size**: 0KB (no build process)
- **Dependencies**: GSAP CDN only

## File Structure

```
Self_website/
├── index.html              # Main page
├── experience.html         # Work experience
├── education.html          # Academic background
├── certifications.html     # Professional certifications
├── projects/               # Interactive project demos
├── styles.css              # CSS with CSS Grid/Flexbox
├── script.js               # WebsiteEnhancer class
├── assets/                 # Images and documents
└── README.md
```

## Setup

```bash
git clone [repo-url]
cd Self_website
# Open index.html in browser - no build process required
```

## Browser Support

- Chrome 80+, Firefox 75+, Safari 13+, Edge 80+
- Progressive enhancement for older browsers

## Key Optimizations

- **Event Handling**: Debounced scroll (150ms), throttled mouse (16ms)
- **Resource Loading**: Critical images preloaded, non-critical lazy loaded
- **Memory Management**: Event listener cleanup, interval clearing
- **Animation Performance**: Hardware acceleration, transform3d, will-change

## Accessibility Features

- Semantic HTML structure
- ARIA landmarks and labels
- Keyboard navigation (Tab, Enter, Escape)
- Focus indicators and skip links
- Screen reader compatibility

---

**Built with vanilla web technologies for maximum performance and compatibility**

