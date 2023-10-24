# Hello-world
# test word 
npm install semver

echo "### Hello world! :rocket:" >> $GITHUB_STEP_SUMMARY

      - name: Set color
        id: color-selector
        run: echo "SELECTED_COLOR=green" >> "$GITHUB_OUTPUT"
      - name: Get color
        env:
          SELECTED_COLOR: ${{ steps.color-selector.outputs.SELECTED_COLOR }}
        run: echo "The selected color is $SELECTED_COLOR"

echo "{environment_variable_name}={value}" >> "$GITHUB_ENV"
steps:
  - name: Set the value in bash
    id: step_one
    run: |
      {
        echo 'JSON_RESPONSE<<EOF'
        curl https://example.com
        echo EOF
      } >> "$GITHUB_ENV"

name: GitHub Script
                uses: actions/github-script@v2.1.0
            
