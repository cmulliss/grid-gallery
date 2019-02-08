# CSS-grid

npm install react-router-dom --save
npm i styled-components

## styled components & template literals

* use backticks for template literals
* then can write regular css inside
* AND can write js inside the template
* now declaring styles inside a react component

```javascript
const Button = styled.button`

display: inline-block;
border-radius: 3px;
border:2px solid palevioletred;
olor: palevioletred;
padding: 05rem 0;
margin: 0.5rem 1 rem;

${props => props.primary && css`
background: palevioletred;
color: white;
`}
`
const container = styled.div`
text-align: center;
`
```

* 