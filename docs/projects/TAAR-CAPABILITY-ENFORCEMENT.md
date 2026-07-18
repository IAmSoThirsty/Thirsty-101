# TAAR Capability Enforcement

## Purpose

TAAR — Trusted Agent Authority Runtime — exists to govern whether an agent may run, what authority it has, what evidence it must produce, and how the run is audited.

The central lesson preserved here is that declared authority is not the same thing as enforced authority.

A policy may say that a reader is read-only. If the process can still write to `/tmp`, modify the repository, access the network, inherit secrets, or spawn unrestricted child processes, the authority exists only as a statement.

The target