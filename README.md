Commit message format:    <type>(<scope>): <subject>
                          <BLANK LINE>
                          <body>

    <type>:
        build: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
        ci: Changes to our CI configuration files and scripts (example scopes: Circle, BrowserStack, SauceLabs)
        docs: Documentation only changes
        feat: A new feature
        fix: A bug fix
        perf: A code change that improves performance
        refactor: A code change that neither fixes a bug nor adds a feature
        style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
        test: Adding missing tests or correcting existing tests

    <subject>:
        use the imperative, present tense: "change" not "changed" nor "changes"
        don't capitalize first letter
        no dot (.) at the end

    <body>:
        azure item id
        optinal: The body should include the motivation for the change and contrast this with previous behavior.

    example: 
        fix(operators): add divide as named export
        feat(operators): add multiply method
        refactor(math): rename math module to operators