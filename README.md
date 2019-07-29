# Generate an Invoice PDF using Cloudflare Workers

## Direct PDF generation

Visit https://generate.invoice.workers.dev to view a PDF generated with all of the default input values.

To customize, set query params `company`, `customer`, `description`, `amount`, and `total`:

<pre>
https://generate.invoice.workers.dev/
  ?company=Ginza Natsuno \n4F Marunouchi 1-5-1 \nChiyoda-ku, Tokyo, Japan
  &customer=Sukiyabashi Jiro \n2-15, Ginza 4-chome \nCity Chuo, Tokyo, Japan
  &description=4 pairs of rounded red sandalwood chopsticks
  &amount=4 × ¥8,000 per pair
  &total=¥32,000
</pre>

[View example PDF](https://generate.invoice.workers.dev/?company=Ginza+Natsuno%0D%0A4F+Marunouchi+1-5-1%0D%0AChiyoda-ku%2C+Tokyo%2C+Japan&customer=Sukiyabashi+Jiro%0D%0A2-15%2C+Ginza+4-chome%0D%0ACity+Chuo%2C+Tokyo%2C+Japan&description=4+pairs+of+rounded+red+sandalwood+chopsticks&amount=4+×+¥8%2C000+per+pair&total=¥32%2C000&number=373267)

## Website

You can also generate a PDF using a UI by visiting [lazy.invoice.workers.dev](https://lazy.invoice.workers.dev), for which this backend Cloudflare Worker script was built.

## License

MIT
