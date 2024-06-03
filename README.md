# ghost-inspectpr-mdoq-pras


Add to your MDOQ PRAs script like
```bash

"$ARGUMENT_STEP_FINAL-$ARGUMENT_COMPARISON_AHEAD")
            set -xe
            # do something
            curl -s https://raw.githubusercontent.com/zero1limited/ghost-inspector-mdoq-pras/master/post-rollup-actions | bash
            ;;
        "$ARGUMENT_STEP_FINAL-$ARGUMENT_COMPARISON_IDENTICAL")
            set -xe
            # do something
            curl -s https://raw.githubusercontent.com/zero1limited/ghost-inspector-mdoq-pras/master/post-rollup-actions | bash
            ;;
        "$ARGUMENT_STEP_FINAL-$ARGUMENT_COMPARISON_BEHIND")
            set -xe
            # do something
            curl -s https://raw.githubusercontent.com/zero1limited/ghost-inspector-mdoq-pras/master/post-rollup-actions | bash
            ;;
        *)

```
