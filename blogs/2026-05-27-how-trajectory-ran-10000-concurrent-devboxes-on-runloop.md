---
title: "How Trajectory ran 10,000 concurrent devboxes on Runloop"
url: "https://runloop.ai/blog/runloop-trajectory-launch-partner-announcement"
date: "2026-05-27"
author: ""
feed_url: "https://runloop.ai/blog"
---
Trajectory, the continual learning platform, consistently runs 10,000+ burst concurrent devboxes on Runloop for training and fine-tuning models. Their workload looked nothing like a demo: many concurrent sessions, long-poll control loops, older Ubuntu blueprints with pinned dependency graphs on top.
