# gym-starter
Starter code for OpenAI Gym, following the documentation at [https://github.com/openai/gym/blob/master/docs/creating-environments.md](https://github.com/openai/gym/blob/master/docs/creating-environments.md).

Make sure to also check out [https://gym.openai.com/docs/](https://gym.openai.com/docs/).

# Setup
1. Either clone this repo and copy all the content to your own empty repo or click the `Use this template` button next to the `Clone or download` button 
2. Replace "foo" with the name of your new gym-environment for all files and folders
4. Add content inside `gym_foo/envs/foo_env.py`. This is where all the work is done

# Usage
1. Install your package with `pip install -e gym-foo`
2. Use `gym.make('gym_foo:foo-v0')` to create an object of this environment