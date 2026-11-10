source "https://rubygems.org"

gem "metanorma-cli", github: "metanorma/metanorma-cli", branch: "main"
gem "metanorma-standoc", github: "metanorma/metanorma-standoc", branch: "main"
gem "metanorma-ietf", github: "metanorma/metanorma-ietf", branch: "main"
# metanorma 2.5.14+ requires Relaton::Render::Unrenderable, which the
# released relaton-render (3.0.0) does not define — isodoc#882/#883
# broke the same way. Ride git main until a 3.1.x release cuts.
gem "relaton-render", github: "relaton/relaton-render", branch: "main"
gem "debug"
