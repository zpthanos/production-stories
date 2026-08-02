# Payoneer and FunnelKit compatibility conflict

[← All production stories](../README.md)

`WooCommerce` `Plugin compatibility` `Checkout` `Regression testing`

## Situation

A WooCommerce checkout implementation experienced a compatibility issue between Payoneer Checkout and FunnelKit Funnel Builder Pro.

## Task

I needed to identify the interaction, restore the affected checkout workflow, and avoid introducing regressions elsewhere in the purchasing journey.

## Action

I isolated the plugin interaction, reviewed the relevant compatibility and release information, identified that Payoneer Checkout needed to be updated to version 3.5.5 or later, applied the supported update, and regression-tested the complete checkout flow.

## Result

The compatibility issue was resolved and the WooCommerce checkout journey operated correctly after the update.

## CV-ready summary

> Diagnosed a compatibility issue between Payoneer Checkout and FunnelKit, identified the required Payoneer 3.5.5+ update, and regression-tested the complete WooCommerce checkout journey after resolution.
