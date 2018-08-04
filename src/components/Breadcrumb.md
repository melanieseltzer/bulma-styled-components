
#### Seperators
``` js
<div>
  <Breadcrumb >
    <ul>
      <li><a href="/">Bulma</a></li>
      <li><a href="/">Documentation</a></li>
      <li><a href="/">Components</a></li>
      <li className="is-active"><a href="/" >Breadcrumb</a></li>
    </ul>
  </Breadcrumb>
  <Breadcrumb className="has-arrow-separator">
    <ul>
      <li><a href="/">Bulma</a></li>
      <li><a href="/">Documentation</a></li>
      <li><a href="/">Components</a></li>
      <li className="is-active"><a href="/" >Breadcrumb</a></li>
    </ul>
  </Breadcrumb>
  <Breadcrumb className="has-bullet-separator">
    <ul>
      <li><a href="/">Bulma</a></li>
      <li><a href="/">Documentation</a></li>
      <li><a href="/">Components</a></li>
      <li className="is-active"><a href="/" >Breadcrumb</a></li>
    </ul>
  </Breadcrumb>
  <Breadcrumb className="has-dot-separator">
    <ul>
      <li><a href="/">Bulma</a></li>
      <li><a href="/">Documentation</a></li>
      <li><a href="/">Components</a></li>
      <li className="is-active"><a href="/" >Breadcrumb</a></li>
    </ul>
  </Breadcrumb>
  <Breadcrumb className="has-succeeds-separator">
    <ul>
      <li><a href="/">Bulma</a></li>
      <li><a href="/">Documentation</a></li>
      <li><a href="/">Components</a></li>
      <li className="is-active"><a href="/" >Breadcrumb</a></li>
    </ul>
  </Breadcrumb>
</div>
```
#### With Icons
``` js
<Breadcrumb >
  <ul>
    <li>
      <a href="/">
        <Icon className="is-small"><i class="fa fa-home" aria-hidden="true"/></Icon>
        Bulma
      </a>
    </li>
    <li>
      <a href="/">
        <Icon className="is-small"><i class="fa fa-book" aria-hidden="true"/></Icon>
        Documentation
      </a>
    </li>
    <li>
      <a href="/">
        <Icon className="is-small"><i class="fa fa-puzzle-piece" aria-hidden="true"/></Icon>
        Components
      </a>
    </li>
    <li className="is-active">
      <a href="/">
        <Icon className="is-small"><i class="fa fa-thumbs-up" aria-hidden="true"/></Icon>
        Breadcrumb
      </a>
    </li>
  </ul>
</Breadcrumb>
```