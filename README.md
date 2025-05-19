# Tech Adoption Lanes

Tech Adoption Lanes is a framework inspired by the [ThoughtsWorks Tech Radar](https://www.thoughtworks.com/en-sg/radar), modified to reflect the technology landscape of a small organization or individual developer.

An example of a past snapshot of my personal lanes: 

<br>

| | Assess | Trial | Adopt | Hold |
| - | ------ | ----- | ----- | ---- |
|Languages<br>& Frameworks |<li>Rust</li>|<li>NextJS</li><li>React Native</li><li>NestJS</li>|<li>JavaScript</li><li>TypeScript</li><li>Python</li><li>ExpressJS</li><li>Vite + ReactJS</li>|<li>Ruby + Ruby on Rails</li><li>Dart + Flutter</li><li>AngularJS</li><li>Create React App</li><li>C/C++</li>|
|Tools |<li>GraphQL</li>|<li>Cucumber</li><li>Playwright</li><li>Metro</li><li>Radix</li>|<li>Nx</li><li>K8s & Docker</li><li>Jest</li><li>PostgreSQL</li><li>Markdown</li>|<li>TensorFlow</li><li>Selenium</li>|
|Platforms |<li>Raspberry PI</li>|<li>Azure Cloud</li><li>Novu</li>|<li>Vultr Cloud</li><li>Gitlab & Gitlab CI/CD</li><li>Keycloak</li><li>JIRA</li><li>Camunda Platform</li>|<li>AWS</li><li>Trello</li><li>Metaflow</li><li>BeagleBone black</li><li>Arduino</li>|
|Techniques|<li>Micro FEs</li><li>Event-driven Architecture</li>||<li>User Story Mapping</li><li>Architecture-as-code</li><li>TDD/BDD</li><li>Scrum & Kanban</li><li>Developer Experience</li>|</li><li>Waterfall</li><li>Native Mobile Apps</li><li>Performance</li>|

<br>

Doesn't look the best, but it's an everything-as-code solution that gets the job done. A live-version from my personal site can be found [here](https://www.joeltok.com/tech-stack). 

<!-- ## What this solves

ThoughtWorks' Tech Radar is a useful tool to map a technology stack, but it has several limitations, as highlighted in this [blog post](https://www.joeltok.com/blog/2025-05-everything-as-code-tech-radar-with-markdown).

1. The Tech Radar is not intended to map the state of the organization's tech landscape.
2. There isn't a clear overview of all technologies at a first glance.
3. It is not clear which technologies are more important than others. This limits usefulness for onboarding new developers.
4. Embedding the Radar into Markdown for an everything-as-code approach to documentation is problematic (read: hacky).

We tackle this by relooking at the way we view the tech radar as a tool, and putting it into a format more suitable for markdown (as above).  -->

## Usage

There are two dimensions to the tech adoption lanes, both borrowed directly from the ThoughtWorks Tech Radar. Both have also been reordered to reflect adoption lifecycles and prioritization. 

### Technology Type

Technology types are divided into Languages & Frameworks, Tools, Platforms, and Techniques. Like with the original, it is not always important that technologies are placed into an "exact" category. 

The innovation in this framework is that their order matters. We start with the technologies developers most likely view as more like "building blocks" (languages & frameworks), and move up the levels of abstraction toward solutions (tools and platforms), and approaches (techniques).

This way a new developer to the organization can get a quick sense of what technologies they need to become good at to be as productive as possible. 

### Stage of Adoption

The stages of adoption have also been reordered to reflect a sense of a technology's maturity *within* the organization. 

We start with the least mature technologies, and move along the lanes toward more mature technologies. Hold is sort of an outlier in this regard.

Reversing the directions is a small adjustment, but important to us. The new direction reflects a sense of continual learning and improvement an organization makes as it introduces new technologies into its landscape. 

## Build-your-own in Markdown

Building your own version of the Tech Adoption Lanes is easy. It's essentially a markdown table, using `<li>tech_name</li>` to put each technology into point form. 

A starter table can be copied from below: 

```markdown
| | Assess | Trial | Adopt | Hold |
| - | ------ | ----- | ----- | ---- |
| Languages<br>& Frameworks | <li></li> |  |  |  |
| Tools | <li></li> |  |  |  |
| Platforms | <li></li> |  |  |  |
| Techniques | <li></li> |
```

