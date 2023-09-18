---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
menu:
  logo: logo
  company_name: Bricks
hero: 
  headline:
    one: Your Landing Page
    two: In Minutes!
  subheadline: Perfect for Newsletters, Ebooks, Courses & More. No Overhead. Just Creativity.
  form_action: https://formkeep.com/f/54e720266abb
  input:
    label: Join the waitlist.
    placeholder: Enter your email
    button_text: Notify me
  image:
    url: https://www.maglev.dev/assets/maglev/10-screenshot_02.webp?1690327517
    alt: Product screenshot
who:
  headline:
    one: Built for Content Creators
    two: Like You.
  description: Setting up a landing page shouldn't be difficult. Create a stunning page for your content, be it newsletters, ebooks, or courses, and start promoting your business instantly.
  background_image:
  cards:
    - title: Newsletters
      description: Got a newsletter? Share it with the world. Set up your landing page in minutes and watch your subscriber list grow.
      icon: mail
    - title: Ebooks
      description: Share a sneak peek or the entire essence of your ebook. Create a landing page swiftly and let eager readers drop their emails for more.
      icon: book
    - title: Courses
      description: Whether you're launching a new course or promoting an existing one, get your audience on board quickly with an easy-to-setup landing page.
      icon: course
problem:
  problem_statement:
    title: The problem with current solutions
    description: For a tool designed to create, most platforms throw users into a maze of confusing interfaces, leaving them to spend more time figuring things out than actually creating.
    image:
      url: https://images.unsplash.com/photo-1456406644174-8ddd4cd52a06?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2048&q=80
      alt: Frustrated content creator
  solution_statement:
    title: Simplicity at its core
    description: With pre-designed, adaptable themes, set up your landing page in a matter of minutes. Spend more time on your content, and less on setup.
    image: 
      url: https://www.maglev.dev/assets/maglev/15-screenshot_02.webp?1690327517
      alt: Bricks builder screenshot
features:
  headline:
    one: Elevate Your
    two: Content Reach
  subheadline: In minutes, launch a landing page tailored for your newsletters, ebooks, or courses. Capture more leads effortlessly.
  cards:
    - title: Seamless Themes
      description: Choose from themes crafted especially for content creators. Capture attention from the get-go.
      icon: badge
    - title: Effortless Customization
      description: Effortless Customization. Personalize to fit your brand with ease. No coding needed.
      icon: lego
    - title: Instant Publish
      description: Your landing page goes live with a click. Start collecting emails in no time.
      icon: trending
subscribe:
  headline:
    one: Get notified
    two: when we’re launching.
  subheadline: Sign up now and be among the first to try our no-code landing page builder.
  input:
    placeholder: Enter your email
    button_text: Notify me
    action:
      url: https://formkeep.com/f/54e720266abb
footer:
  company_name: Bricks
---

{% include hero.html %}
{% include whoisthisfor.html %}
{% include problem.html %}
{% include features.html %}
{% include cta.html %}
{% include footer.html %}
