### Hi there 👋

<img align="left" src="https://github-readme-stats.vercel.app/api?username=felbinger&theme=dark">
<img align="right" src="https://github-readme-stats.vercel.app/api/top-langs/?username=felbinger&theme=dark">

[![Visits](https://badges.pufler.dev/visits/felbinger/felbinger?style=flat-square&color=black&logo=github)](https://github.com/felbinger)
[![Years](https://badges.pufler.dev/years/felbinger?style=flat-square&color=black&logo=github)](https://github.com/felbinger)
[![Repos](https://badges.pufler.dev/repos/felbinger?style=flat-square&color=black&logo=github)](https://github.com/felbinger?tab=repositories)
[![Gists](https://badges.pufler.dev/gists/felbinger?style=flat-square&color=black&logo=github)](https://gist.github.com/felbinger)
[![Monthly Commits](https://badges.pufler.dev/commits/monthly/felbinger?style=flat-square&color=black&logo=github)](https://github.com/felbinger)

### :construction_worker: Check out what I'm currently working on
{{range recentContributions 5}}
- [{{.Repo.Name}}]({{.Repo.URL}}){{ with .Repo.Description }} - {{ . }}{{ end }} ({{humanize .OccurredAt}})
{{- end}}

### :seedling: My latest projects
{{range recentRepos 5}}
- [{{.Name}}]({{.URL}}){{ with .Description}} - {{ . }}{{ end }}
{{- end}}

### :telescope: Latest releases I've contributed to
{{range recentReleases 5}}
- [{{.Name}}]({{.URL}}) ([{{.LastRelease.TagName}}]({{.LastRelease.URL}}), {{humanize .LastRelease.PublishedAt}}){{ with .Description}} - {{ . }}{{ end }}
{{- end}}
