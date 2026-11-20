# github.css
  border-radius: 16px;
  box-shadow: 0 8px 24px rgba(20, 33, 61, 0.06);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.card:hover {
  transform: translateY(-3px);
  box-shadow: 0 12px 28px rgba(20, 33, 61, 0.1);
}

h2 {
  margin: 0 0 16px;
  color: var(--navy);
  padding-bottom: 10px;
  border-bottom: 2px solid var(--light-blue);
}

p {
  margin: 0;
}

ul {
  margin: 0;
  padding-left: 22px;
}

.hobby-list,
.subject-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 10px;
}

li::marker {
  color: var(--blue);
}

.table-wrap {
  width: 100%;
  overflow-x: auto;
}

table {
  width: 100%;
  border-collapse: collapse;
  min-width: 540px;
}

th, td {
  padding: 13px 15px;
  border: 1px solid var(--border);
  text-align: left;
}

th {
  background: var(--navy);
  color: white;
}

tbody tr:nth-child(even) {
  background: #f7f9fd;
}

tbody tr:hover {
  background: var(--light-blue);
}

.total-row,
.result-row {
  font-weight: bold;
  background: #eaf2ff !important;
}

.contact {
  border-left: 5px solid var(--blue);
}

footer {
  text-align: center;
  padding: 22px;
  background: var(--navy);
  color: #dce6f7;
  font-size: 0.9rem;
}

@media (max-width: 600px) {
  .hero {
    padding: 42px 16px;
  }

  .card {
    padding: 18px;
  }

  th, td {
    padding: 10px;
  }
}
