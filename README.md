# Green-earth-landscaping-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Green Earth Landscaping</title>
  <meta name="description" content="Eco-friendly landscaping services for homes and businesses." />
</head>
<body>

  <!-- Simple site header and navigation -->
  <header>
    <h1>Green Earth Landscaping</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#blog">Blog</a></li>
        <li><a href="#quote">Get a Quote</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <hr />
  </header>

  <!-- HOME -->
  <main id="home">
    <h2>Welcome</h2>
    <p>
      We create sustainable, beautiful outdoor spaces for homes, businesses, and public areas.
      Our focus is eco-friendly design, water-wise planting, and long-term maintenance that
      respects the environment.
    </p>
    <p><a href="#services">Explore our services</a> or <a href="#quote">request a free quote</a>.</p>
    <figure>
      <img src="placeholder-hero.jpg" alt="Lush, eco-friendly garden landscape" />
      <figcaption>Before and after projects available in our portfolio below.</figcaption>
    </figure>
    <hr />
  </main>

  <!-- ABOUT -->
  <section id="about">
    <h2>About Us</h2>
    <p>
      Founded in 2012, Green Earth Landscaping transforms outdoor areas into sustainable,
      functional, and inspiring spaces. We serve residential, commercial, and municipal clients.
    </p>
    <h3>Mission & Values</h3>
    <ul>
      <li>Sustainability and environmental care</li>
      <li>Quality workmanship and client satisfaction</li>
      <li>Innovative, practical landscape design</li>
    </ul>

    <h3>Who We Serve</h3>
    <ul>
      <li>Homeowners and property managers</li>
      <li>Local businesses and organizations</li>
      <li>Environmental enthusiasts and communities</li>
    </ul>
    <hr />
  </section>

  <!-- SERVICES -->
  <section id="services">
    <h2>Services</h2>
    <p>Here is an overview of our core service areas.</p>

    <article>
      <h3>Eco-Friendly Landscape Design</h3>
      <p>
        Water-wise planting plans, soil improvement, and native plant selections that thrive
        with minimal inputs.
      </p>
    </article>

    <article>
      <h3>Garden Installation</h3>
      <p>
        From layout and planting to paths and beds, we build gardens that grow healthier each season.
      </p>
    </article>

    <article>
      <h3>Lawn & Garden Maintenance</h3>
      <p>
        Pruning, mulching, weed control, and seasonal clean-ups to keep your space looking great.
      </p>
    </article>

    <article>
      <h3>Commercial & Municipal Projects</h3>
      <p>
        Scalable solutions for campuses, retail centers, and public spaces with an emphasis on durability.
      </p>
    </article>

    <h3>Estimated Pricing (Guide)</h3>
    <table>
      <caption>Typical project ranges (exact quotes provided after site visit)</caption>
      <thead>
        <tr>
          <th>Service</th>
          <th>Small Project</th>
          <th>Medium Project</th>
          <th>Large Project</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Design & Plan</td>
          <td>R3,000 – R7,000</td>
          <td>R7,000 – R15,000</td>
          <td>R15,000+</td>
        </tr>
        <tr>
          <td>Installation</td>
          <td>R8,000 – R20,000</td>
          <td>R20,000 – R60,000</td>
          <td>R60,000+</td>
        </tr>
        <tr>
          <td>Maintenance (monthly)</td>
          <td>R800 – R2,000</td>
          <td>R2,000 – R6,000</td>
          <td>R6,000+</td>
        </tr>
      </tbody>
    </table>
    <p><em>Note:</em> Final pricing depends on site conditions and scope.</p>
    <hr />
  </section>

  <!-- PORTFOLIO -->
  <section id="portfolio">
    <h2>Portfolio</h2>
    <p>Selected projects. Click a thumbnail to view the full image (placeholder links).</p>

    <ul>
      <li>
        <a href="project1-full.jpg">
          <img src="project1-thumb.jpg" alt="Residential garden with native plants" />
        </a>
        <p>Residential Native Garden</p>
      </li>
      <li>
        <a href="project2-full.jpg">
          <img src="project2-thumb.jpg" alt="Commercial courtyard with low-water plants" />
        </a>
        <p>Commercial Courtyard</p>
      </li>
      <li>
        <a href="project3-full.jpg">
          <img src="project3-thumb.jpg" alt="Before and after lawn conversion" />
        </a>
        <p>Lawn-to-Garden Conversion</p>
      </li>
    </ul>

    <h3>Testimonials</h3>
    <blockquote>
      “They turned our water-hungry lawn into a thriving, low-maintenance garden. Highly recommended!”
    </blockquote>
    <hr />
  </section>

  <!-- BLOG -->
  <section id="blog">
    <h2>Blog</h2>
    <article>
      <h3>5 Water-Wise Planting Tips</h3>
      <p>
        Choose native species, group plants by water needs, and mulch to retain soil moisture.
        Simple steps can dramatically reduce water use.
      </p>
      <a href="#contact">Ask us about plant choices</a>
    </article>

    <article>
      <h3>Composting Basics</h3>
      <p>
        Compost enriches soil and reduces waste. Start with a simple bin and balance greens and browns.
      </p>
      <a href="#quote">Request a soil assessment</a>
    </article>
    <hr />
  </section>

  <!-- QUOTE REQUEST FORM -->
  <section id="quote">
    <h2>Request a Free Quote</h2>
    <p>Tell us about your project and we’ll get back to you.</p>
    <form action="#" method="post">
      <fieldset>
        <legend>Your Details</legend>
        <label for="q-name">Full Name</label><br />
        <input id="q-name" name="name" type="text" required /><br /><br />

        <label for="q-email">Email</label><br />
        <input id="q-email" name="email" type="email" required /><br /><br />

        <label for="q-phone">Phone</label><br />
        <input id="q-phone" name="phone" type="tel" /><br /><br />
      </fieldset>

      <fieldset>
        <legend>Project Info</legend>
        <label for="q-location">Location/City</label><br />
        <input id="q-location" name="location" type="text" /><br /><br />

        <label for="q-service">Service Needed</label><br />
        <select id="q-service" name="service">
          <option value="design">Eco-friendly Design</option>
          <option value="installation">Garden Installation</option>
          <option value="maintenance">Maintenance</option>
          <option value="commercial">Commercial/Municipal</option>
        </select><br /><br />

        <label for="q-notes">Brief Description</label><br />
        <textarea id="q-notes" name="notes" rows="5" cols="40" placeholder="Tell us about your space and goals."></textarea>
      </fieldset>

      <p>
        <button type="submit">Send Request</button>
      </p>
    </form>
    <hr />
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <h2>Contact</h2>
    <p>
      Email: <a href="mailto:greenlandscaping@gmail.com">greenlandscaping@gmail.com</a><br />
      Phone: <a href="tel:+0000000000">+00 000 0000</a><br />
      Address: 123 Green Way, Eco Park
    </p>

    <h3>Quick Contact Form</h3>
    <form action="#" method="post">
      <label for="c-name">Name</label><br />
      <input id="c-name" name="name" type="text" required /><br /><br />

      <label for="c-email">Email</label><br />
      <input id="c-email" name="email" type="email" required /><br /><br />

      <label for="c-message">Message</label><br />
      <textarea id="c-message" name="message" rows="4" cols="40"></textarea><br /><br />

      <button type="submit">Send</button>
    </form>
    <hr />
  </section>

  <!-- FOOTER -->
  <footer>
    <p>&copy; 2012–2025 Green Earth Landscaping. All rights reserved.</p>
    <p>
      <a href="#home">Back to top</a>
    </p>
  </footer>

</body>
</html>
