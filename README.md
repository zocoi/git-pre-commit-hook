## git pre-commit hook for web development

Ensures that changes to the project may only be committed if there is no logging or debugging methods included.
Current keywords: "Rails.logger", "console.log"

### Use internally in the project

    cd rails_project
    wget https://github.com/zocoi/git-pre-commit-hook/raw/master/pre-commit
    mv pre-commit /.git/hooks/
    chmod +x .git/hooks/pre-commit

### Use globally

    wget https://github.com/zocoi/git-pre-commit-hook/raw/master/pre-commit
    mv pre-commit /usr/local/share/git-core/templates/hooks/
    chmod +x /usr/local/share/git-core/templates/hooks/
