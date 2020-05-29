# gym-starter
Starter code for Open-AI Gym, following the documentation at [https://github.com/openai/gym/blob/master/docs/creating-environments.md](https://github.com/openai/gym/blob/master/docs/creating-environments.md)

Make sure to also check out [https://gym.openai.com/docs/](https://gym.openai.com/docs/)

# Setup
1. Clone this repo
2. Copy all the content to your own empty repo
3. Replace "foo" with the name of your gym-environment for all files and folders
4. Add content inside `gym_foo/envs/foo_env.py`. This is where all the work is done

# Usage
1. Install your package with `pip install -e gym-foo`
2. Use `gym.make('gym_foo:foo-v0')` to create an object of this environment