# Catena-X Simulation

This document gives additional context to the models in the namespace `urn:samm:io.catenax.simulation_model`. These models belong to the MBSE working group and are further explained in the Simulation KIT.

These currently include:

| Model Name | urn |
| ---------- | --- |
| [Minimal Simulation Model](#simulation-minimal) | ``urn:samm:io.catenax.simulation_model.minimal:1.6.0`` |
| Simulation Context | ``urn:samm:io.catenax.simulation_model.context:1.0.0`` |
| Simulation SIC | ``urn:samm:io.catenax.simulation_model.shared.sic_core:1.0.0`` |

## Simulation Minimal

Current Turtle-File: [``simulation_model.minimal:1.6.0``](./1.0.0/SimulationModel.ttl)

This model was initially created as a model consuming most relevant aspects from [MIC core](https://mic-core.github.io/MIC-Core/main/#_introduction).

## Simulation Context (not yet committed)

Current Turtle-File: [`simulation_model.context:1.0.0`](1.0.0/SimulationContext.ttl)

## Simulation SIC

Current Turtle-File: [``simulation_model.shared.sic_core``](./1.0.0/SimulationSICCore.ttl)

This model is a shared model addressing the mandatory [SIC Core](https://mic-core.github.io/SIC-Core/main/#_introduction) attributes.
While the sub-attributes are optional in the specification they are partly set to mandatory in this standard as mentioned in [SIC Core Composite Attributes Section](https://mic-core.github.io/SIC-Core/main/#_composite_attributes).
