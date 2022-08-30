# Tabelas

Tabelas são muito úteis quando precisamos inserir um grande número de informações da forma mais organizada possível.

```html
<table>
  <tr>
    <th>Empresa</th>
    <th>Telefone</th>
    <th>Cidade</th>
  </tr>
  <tr>
    <td>Hospital Copa D'Or</td>
    <td>(21) 2545-3600</td>
    <td>Rio de Janeiro</td>
  </tr>
  <tr>
    <td>Hospital Israelita Albert Einstein Morumbi</td>
    <td>(11) 2151-1233</td>
    <td>São Paulo</td>
  </tr>
  <tr>
    <td>Hospital Brasília</td>
    <td>(61) 3704-9000</td>
    <td>Brasília</td>
  </tr>
  <tr>
    <td>Hospital São Lucas</td>
    <td>(31) 3238-8568</td>
    <td>Belo Horizonte</td>
  </tr>
</table>
```

## Tabelas com rowspan e colspan

```html
<table border="1">
    <thead>
      <td></td>
      <td>Segunda</td>
      <td>Terça</td>
      <td>Quarta</td>
      <td>Quinta</td>
      <td>Sexta</td>
    </thead>
    <tbody>
      <tr>
        <td>08:00</td>
        <td colspan="2">Mat</td>
        <td>Ed. Fís.</td>
        <td>Port</td>
        <td>Ing.</td>
      </tr>
      <tr>
        <td>09:00</td>
        <td>Hist.</td>
        <td rowspan="2">Física</td>
        <td>Hist.</td>
        <td>Mat</td>
        <td>Bio</td>
      </tr>
      <tr>
        <td>10:00</td>
        <td rowspan="2">Química</td>
        <td colspan="3">Geografia</td>
      </tr>
      <tr>
        <td>11:00</td>
        <td>Ed. Física</td>
        <td>Mat.</td>
        <td colspan="2">Port.</td>
      </tr>
    </tbody>
  </table>
```