<p align="center">
  <img src="https://github.com/user-attachments/assets/059c897f-763e-4482-aad3-ac196e72de36" alt="Victor Client logo" width=45%/>
</p>

Victor Client
=======

<b>Victor Client</b> is a custom launcher for Minecraft that focuses on predictability, long term stability and quality of life minecraft mods.

## Development
If you want to contribute, talk to us on <b>[Discord](https://discord.gg/multimc)</b> first.
<img src="https://github.com/user-attachments/assets/e3e1e029-626f-4a3e-a621-0f7241a16b9e" alt="Victor Client Discord"/>

While blindly submitting Applications is definitely possible, they're <b>not</b> necessarily going to get accepted.

We are looking for <b>flashy features</b>,and expanding upon the existing feature set <b>without</b> disruption or endangering the future viability of the project is prefered.

### Donating
If you want to Donate to help with ongoing project visit the <b>[Website](https://victorclient2.godaddysites.com)</b>

### Code formatting
Just follow the existing formatting.

In general, in order of importance:
* Make sure your IDE is not messing up line endings or whitespace and avoid using linters.
* Prefer readability over dogma.
* Keep to the existing formatting.
* Indent with 4 space unless it's in a submodule.
* Keep lists (of arguments, parameters, initializers...) as lists, not paragraphs. It should either read from top to bottom, or left to right. Not both.

## Translations
Translations can be done [on crowdin](https://translate.multimc.org). Please avoid making direct pull requests to the translations repository.

## License
Copyright &copy; 2013-2022 MultiMC Contributors

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this program except in compliance with the License. You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0).

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

## Forking/Redistributing/Custom builds policy
<b>We keep Launcher open source because we think it's important to be able to see the source code for a project like this, and we do so using the Apache license.</b>

The license gives you access to the source <b>Victor Client</b> is built from, but not:
- The name, logo and other branding.
- The API tokens required to talk to services that the launcher depends on.

Because of the nature of the agreements required to interact with the Microsoft identity platform, it's impossible for us to continue allowing everyone to build the code as 'Victor Client'. The source code has been debranded and now builds as `DevLauncher` by default.

You must provide your own branding if you want to distribute your own builds.

You will also have to register your own app on Azure to be able to handle Microsoft account logins.

If you decide to fork the project, a mention of its origins in the About dialog and the license is acceptable. However, it should be abundantly clear that the project is a fork <b>*without*</b> implying that you have our blessing.
