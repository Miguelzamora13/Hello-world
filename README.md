# Hello-world
# test word 
echo "### Hello world! :rocket:" >> $GITHUB_STEP_SUMMARY
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
            
