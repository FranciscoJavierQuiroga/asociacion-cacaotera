# Gemfile para desarrollo local del sitio Jekyll
source "https://rubygems.org"

# Gema principal de Jekyll
gem "jekyll", "~> 4.3.0"

# Tema por defecto
gem "minima", "~> 2.5"

# Plugins compatibles con GitHub Pages
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Para desarrollo en Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Para mejorar el rendimiento en desarrollo
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Para compatibilidad con GitHub Pages
gem "github-pages", group: :jekyll_plugins
