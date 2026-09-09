# Agora

A debate arena: five agents with fixed personas argue an open-ended question,
and a Judge agent evaluates the exchange and returns a verdict with reasoning.

Specified and built with the AWS AI-DLC methodology (awslabs/aidlc-workflows
2.8.1, Claude Code harness). The lifecycle artifacts under `aidlc/` — intent
capture, scope, requirements, unit breakdown — are the record of how the system
was specified before it was built. The framework runtime is not committed;
install it and run `aidlc config --harness claude`.
