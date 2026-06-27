form action="https://formspree.io/f/DEIN_FORM_ID" method="POST">
  <input type="text" name="name" placeholder="Dein Name" required>
  <input type="tel" name="phone" placeholder="Telefon" required>
  <textarea name="address" placeholder="Lieferadresse" required></textarea>
  <!-- Verstecktes Feld für Bestellzusammenfassung -->
  <input type="hidden" name="order_summary" id="orderSummary">
  <button type="submit">Bestellung aufgeben</button>
</form>
