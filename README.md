# the-setup

## Usage

```
pipenv run ansible-playbook -i hosts main.yml
```

# Tips

```
mas list | perl -lne 'printf "- {id: $1,\tname: \"$2\"}\n" if /([^\s]*)\s(.*)/'
```
