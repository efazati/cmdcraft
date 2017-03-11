# Dead code
vulture ./project

# lint checker
pylint --rcfile=.pylintrc ./project > pylint_result

# fix pep8 and unused imports and unused variables
autopep8 --in-place --aggressive -r ./*
autoflake --in-place --remove-all-unused-imports --remove-unused-variables --recursive .

find . -name "*.pyc" -exec rm -rf {} \;