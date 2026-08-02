# Accessibility-related checkout defect

[← All production stories](../README.md)

`Accessibility` `Checkout` `axe DevTools` `Cross-browser testing`

## Situation

A checkout form was failing to process submitted customer information correctly because of improper email-field handling.

## Task

I needed to determine whether the problem came from the form markup, validation, or browser-specific behaviour and restore the checkout journey.

## Action

I investigated the form using axe DevTools, browser inspection, and manual testing, corrected the email-field semantics and associated handling, and completed regression testing across browsers and device sizes.

## Result

The form could submit the required information correctly, while the implementation also provided more appropriate accessible input behaviour.

## CV-ready summary

> Diagnosed an accessibility-related checkout submission defect using axe DevTools and browser inspection, corrected email-field handling, and regression-tested the restored journey across browsers and devices.
