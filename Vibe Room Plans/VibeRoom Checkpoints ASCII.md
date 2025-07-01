p2
+------------------------+
| 1. CI/CD Pipeline      |
+------------------------+
        |
        +-- Define branching strategy
        +-- Setup CI/CD tool
        +-- Configure environments
        |     +-- dev
        |     +-- test
        |     +-- prod
        +-- Automate deployment
        +-- Add rollback mechanism
        +-- Monitoring/logging integration

p1
+------------------------+
| 2. Latency Testing     |
+------------------------+
        |
        +-- Simulate low-bandwidth
        +-- Test packet loss/jitter
        +-- Multi-user latency (5-50+)
        +-- Audio/Video/Screen tests
        +-- Mobile vs Desktop tests
        +-- Geo-distributed testing (can not be done right now)
        +-- Establish performance baseline 

p1
+------------------------------+
| 3. Mediasoup Optimization    |
+------------------------------+
        |
        +-- Review official docs
        +-- Tune transports (UDP/TCP)
        +-- Router & worker tuning
        +-- Enable Simulcast/SVC
        +-- Test SFU configurations
        +-- Setup latency profiling
        +-- Sample project audits
        +-- Edge server optimization (can not be done right now)

p2
+-------------------------------+
| 4. Producer & Consumer Control |
+-------------------------------+
        |
        +-- Mute/unmute & volume
        +-- Device switching
        +-- Stream priority/pause
        +-- Admin tools (kick, spotlight) (can not be done right now)
        +-- Permission handling

+----------------------+
| 5. UI/UX Optimization|
+----------------------+
        |
        +-- Schedule design workshop
        +-- Identify UI friction points
        +-- Build & test prototypes
        +-- Cross-device testing
        +-- Dark/light mode support

+-----------------------------+
| 6. Highloka Integration     |
+-----------------------------+
        |
        +-- Review existing pipeline
        +-- Define integration points
        +-- Schema compatibility
        +-- Shared auth/session setup
        +-- Test integration flows
              +-- Clip export
              +-- Session save/load
              +-- Playback flow
