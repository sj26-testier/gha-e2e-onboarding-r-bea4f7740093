# Cobra Windows compatibility lab r-bea4f7740093

Upstream: https://github.com/spf13/cobra/tree/adbc8813901bba65827259daa8e22ff94ec1f30e
Apache-2.0 license retained verbatim in LICENSE.txt.
All66 upstream files/modes preserved; original workflows archived under
.lab/upstream-workflows. Active test.yml retains the complete upstream test-win
job unchanged, including MSYS2 setup, cache, richgo/gox and make richtest.
Only unrelated Linux/macOS jobs and PR-labeler workflow are excluded from execution.
No publishing, upstream CI, or release scripts are invoked. This is a Windows-job
slice, not full upstream matrix parity.
