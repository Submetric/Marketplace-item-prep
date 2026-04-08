# FAQ

## General

### What does Marketplace Item Prep do?

It helps creators prepare cleaner Marketplace avatar item thumbnails in Roblox Studio through scene setup, framing, backdrop control, lighting control, and review-oriented composition tools.

### Who is it for?

It is aimed at creators who prepare Marketplace avatar item thumbnails and want a faster, cleaner workflow inside Studio.

### Is this a Creator Store product or a Marketplace tool?

Both, in different ways.

The plugin itself is distributed as a creator tool. Its day-to-day workflow target is Marketplace avatar item thumbnail preparation.

### Does the plugin silently modify my source asset during preview?

The public `Lite` and `Pro` workflows are documented as non-destructive preview workflows. `Stage Shot` uses plugin-owned preview content for composition work instead of silently applying publish-facing changes during preview.

## Workflow

### What is the difference between World Shot and Stage Shot?

`World Shot` keeps the current place context.

`Stage Shot` creates an isolated plugin-owned preview scene for cleaner composition work.

### When should I use Frame?

Use `Frame` early in the workflow to get a stable starting composition before doing more detailed adjustments.

### What does Reset do?

`Reset` helps bring the camera workflow back to a cleaner starting point if the shot has become over-adjusted.

### What does Clean Stage do?

It removes the plugin-owned preview stage so you can return to a cleaner world-state workflow.

## Lite And Pro

### What is included in Lite?

`Lite` includes valid target detection, `World Shot`, `Stage Shot`, camera presets, `Frame`, `Reset`, basic backdrop and lighting swatches, stage cleanup and return actions, and last-used settings.

### What is included in Pro?

`Pro` includes everything in `Lite`, then adds `Quick Compose`, `Fine Tune` camera controls, full background palette access, advanced lighting controls, review candidate apply, `Scene Presets`, and `Safe Framing Guardrail`.

### Is Lite useful on its own?

Yes. `Lite` is meant to be a usable free baseline, not just a locked shell.

### When should I upgrade to Pro?

Upgrade to `Pro` if you want more control over composition, better scene polish, reusable named scene setups, and safer framing guidance on the current item.

## Pro Features

### What is Quick Compose?

`Quick Compose` is a faster way to steer the shot at a higher level before moving into more detailed camera cleanup.

### What is Fine Tune?

`Fine Tune` provides more detailed camera controls for precise single-item shot adjustment.

### What are Scene Presets?

`Scene Presets` let you save and reload named single-item scene setups.

### What does Safe Framing Guardrail do?

It provides advisory framing guidance to help reduce risky crops and weak fit decisions. It should be understood as guidance, not a guarantee.

## Scope And Limits

### Does Pro include batch or multi-item workflow automation?

No. The current public `Pro` docs position it as a single-item quality tier.

### Can the plugin publish directly to Marketplace for me?

No.

### Does the plugin guarantee Marketplace approval or moderation success?

No.

### Does it replace Accessory Fitting or full validation tools?

No. It is a thumbnail prep and scene review tool, not a full fitting or publishing replacement.

## Troubleshooting And Support

### Why is my selection not detected?

Start with a selected `Accessory`, `Model`, or `MeshPart`, then try again.

### Why does the shot still look wrong after adjustment?

Try pressing `Frame`, simplifying the scene, switching shot mode, or resetting the camera before doing deeper manual refinement.

### Where do I report bugs or feedback?

Open Marketplace Item Prep in Roblox Studio and use `Help > Contact Support`.
