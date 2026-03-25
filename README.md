Here's a README for the StyleVault GitHub Pages repo:

---

# StyleVault UK

Live demo: [naheem1.github.io/stylevault-uk](https://naheem1.github.io/stylevault-uk)

A premium fashion e-commerce storefront — built as the client-facing site for my AWS High Availability infrastructure project.

---

## About

StyleVault UK is a fashion retailer whose single EC2 instance went down for 47 minutes during a Black Friday traffic spike, losing an estimated £2,000 in revenue.

This storefront is the site that was protected by the infrastructure rebuild — ALB + Auto Scaling Group across two Availability Zones in eu-west-2, with the HTML served via S3 and pulled down on instance launch.

---

## Tech

- Pure HTML + CSS — no frameworks, no dependencies
- Hosted on GitHub Pages as a static demo
- In production: served via Apache on EC2 instances behind an AWS Application Load Balancer

---

## Related

The full infrastructure build — architecture, step-by-step ClickOps guide, and all 6 debugging issues documented:

👉 [AWS Auto Scaling + Load Balancer — High Availability Project]


---

Just update the repo link on the last line once you know what you named the infrastructure repo. Want me to create it as a file?
