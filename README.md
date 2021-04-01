# CoffeeForCodeAPI

# Beta Table

<table>
  <thead>
    <tr>
      <th colspan=1>Input</th>
      <th colspan=3>Output</th>
      <th colspan=2>Suggested Handling</th>
    </tr>
  </thead>
  <thead>
    <tr>
      <th>Value</th>
      <th><code>card.type</code></th>
      <th><code>isPotentiallyValid</code></th>
      <th><code>isValid</code></th>
      <th>Render Invalid UI</th>
      <th>Allow Submit</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>''</code></td>
      <td><code>null</code></td>
      <td><strong>true</strong></td>
      <td>false</td>
      <td>no</td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>'6'</code></td>
      <td><code>null</code></td>
      <td><strong>true</strong></td>
      <td>false</td>
      <td>no</td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>'60'</code></td>
      <td><code>'discover'</code></td>
      <td><strong>true</strong></td>
      <td>false</td>
      <td>no</td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>'601'</code></td>
      <td><code>'discover'</code></td>
      <td><strong>true</strong></td>
      <td>false</td>
      <td>no</td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>'6011'</code></td>
      <td><code>'discover'</code></td>
      <td><strong>true</strong></td>
      <td>false</td>
      <td>no</td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>'601'</code></td>
      <td><code>'discover'</code></td>
      <td><strong>true</strong></td>
      <td>false</td>
      <td>no</td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>'60'</code></td>
      <td><code>'discover'</code></td>
      <td><strong>true</strong></td>
      <td>false</td>
      <td>no</td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>'6'</code></td>
      <td><code>null</code></td>
      <td><strong>true</strong></td>
      <td>false</td>
      <td>no</td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>''</code></td>
      <td><code>null</code></td>
      <td><strong>true</strong></td>
      <td>false</td>
      <td>no</td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>'x'</code></td>
      <td><code>null</code></td>
      <td>false</td>
      <td>false</td>
      <td><strong>yes</strong></td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>''</code></td>
      <td><code>null</code></td>
      <td><strong>true</strong></td>
      <td>false</td>
      <td>no</td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>'4'</code></td>
      <td><code>'visa'</code></td>
      <td><strong>true</strong></td>
      <td>false</td>
      <td>no</td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>'41'</code></td>
      <td><code>'visa'</code></td>
      <td><strong>true</strong></td>
      <td>false</td>
      <td>no</td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>'411'</code></td>
      <td><code>'visa'</code></td>
      <td><strong>true</strong></td>
      <td>false</td>
      <td>no</td>
      <td>no</td>
    </tr>
    <tr>
      <td><code>'4111111111111111'</code></td>
      <td><code>'visa'</code></td>
      <td><strong>true</strong></td>
      <td><strong>true</strong></td>
      <td>no</td>
      <td><strong>yes</strong></td>
    </tr>
    <tr>
      <td><code>'411x'</code></td>
      <td><code>null</code></td>
      <td>false</td>
      <td>false</td>
      <td><strong>yes</strong></td>
      <td>no</td>
    </tr>
  </tbody>
</table>
