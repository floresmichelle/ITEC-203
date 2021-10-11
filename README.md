# ITEC-203
Quantitative Method Including Modeling and Simulation
 '<!doctype html><html><head><title>Home</title></head><body><div>Home</div></body></html>'
    )
  })

  it('should load the about page', async () => {
    req.pathname = '/about.html'
const link = i18n.link()
    const result = link('about')
    expect(result).toBe('/about.html')
  })

  it('should return the correct link for deep page', async () => {
    const result = link('docs/about')
    expect(result).toBe('/docs/about.html')
  })

  it('should support url parameters', async () => {
