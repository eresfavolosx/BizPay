# BizPay — B2B Payroll & Payments Portal

[![Live Demo](https://img.shields.io/badge/demo-bizpay.novu.works-0f172a?style=flat-square)](https://bizpay.novu.works)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![License](https://img.shields.io/badge/license-Apache%202.0-blue?style=flat-square)

**BizPay** is a mobile-first commercial payments portal concept for small and mid-sized businesses in Puerto Rico. It brings payroll, employee payments, and **ATH Móvil Business** checkout into a single dashboard so owners can pay staff and vendors from their phones.

> **▶ Live demo:** **[bizpay.novu.works](https://bizpay.novu.works)** · Part of the [NovuWorks portfolio](https://novu.works)

---

## Highlights

| Area | What it does |
| --- | --- |
| **Payments dashboard** | One place to start a payment, see recent activity, and review spending charts |
| **Payroll** | Pay full-time and part-time employees, with a per-employee detail view (`Fulltime-details.html`) |
| **ATH Móvil Business** | Checkout flow built around Puerto Rico's most widely used mobile payment network |
| **Mobile-first UI** | Responsive Bootstrap layout plus an *Add to Home Screen* prompt so it feels like an installed app |
| **Analytics** | Visual summaries of payment and payroll activity |

## Tech Stack

- **Markup / Styling:** HTML5, CSS3, Bootstrap 3 (with theme)
- **Interaction:** jQuery, smooth-scroll navigation, parallax sections
- **Mobile UX:** `addtohomescreen.js` for an installable, app-like experience on iOS and Android

## Project Structure

```text
BizPay/
├── index.html                 # Landing / dashboard entry point
├── styles.css                 # App-level styles
├── Pages/
│   ├── Payments.html          # Payments workflow
│   ├── Payroll.html           # Payroll overview
│   └── Fulltime-details.html  # Employee detail view
├── Assets/
│   ├── CSS/                   # Bootstrap + add-to-home-screen styles
│   └── JS/                    # jQuery, Bootstrap, parallax, app script
└── images/                    # Logo, ATH Móvil mark, chart graphics
```

## Running Locally

There's no build step. It's a static site.

```bash
git clone https://github.com/eresfavolosx/BizPay.git
cd BizPay/BizPay
python3 -m http.server 8080   # or any static file server
# open http://localhost:8080
```

## Project History

- **2016:** Original prototype built (this repository).
- **2025–2026:** Refreshed edition deployed at [bizpay.novu.works](https://bizpay.novu.works), with light/dark themes and a branded intro. Its source ships with the [NovuWorks portfolio](https://github.com/eresfavolosx/novuworks/tree/master/subdomains/bizpay).

See [CHANGELOG.md](CHANGELOG.md) for details.

## Author

**Fabián Vélez Vicente**: [novu.works](https://novu.works) · [GitHub @eresfavolosx](https://github.com/eresfavolosx)

## License

Distributed under the Apache License 2.0. See [`BizPay/LICENSE`](BizPay/LICENSE).
