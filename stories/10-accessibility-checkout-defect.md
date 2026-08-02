<div align="center">

# Accessibility-related checkout defect

**Using accessibility and browser evidence to restore a failed form journey**

`Accessibility` · `Checkout` · `axe DevTools` · `Cross-browser testing`

</div>

> **Outcome:** Corrected email-field handling so the checkout could submit customer information correctly across browsers and device sizes.

## At a glance

| | |
| --- | --- |
| **Journey** | Checkout form submission |
| **Evidence** | axe DevTools, browser inspection and manual testing |
| **Role signal** | Accessibility QA · Defect investigation · Regression testing |

## 1. Situation

A checkout form was failing to process submitted customer information correctly because of improper email-field handling.

## 2. Objective

Determine whether the problem came from form markup, validation or browser-specific behaviour, then restore the checkout journey.

## 3. What I did

- Investigated the form using axe DevTools.
- Inspected the implementation in the browser.
- Reproduced the behaviour manually.
- Corrected the email-field semantics and associated handling.
- Regression-tested across browsers and device sizes.

## 4. Result

The form could submit the required information correctly, while the implementation also provided more appropriate accessible input behaviour.

## Recruiter takeaway

> Diagnosed an accessibility-related checkout submission defect using axe DevTools and browser inspection, corrected email-field handling and regression-tested the restored journey across browsers and devices.

---

[← Previous](09-banking-checkout-integration.md) · [All stories](../README.md) · [Next →](11-pagespeed-improvement.md)
