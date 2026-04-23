<style>
.timeline-container {
  position: relative;
  display: flex;
  flex-direction: column;
  gap: 70px;
  margin-top: 50px;
  color: #e8e8e8;
  font-family: "Inter", sans-serif;
}

/* Ligne centrale plus lumineuse */
.timeline-line {
  position: absolute;
  left: 50%;
  top: 0;
  width: 4px;
  height: 100%;
  background: linear-gradient(#5fb3ff, #9cd8ff);
  transform: translateX(-50%);
  border-radius: 2px;
}

/* Élément */
.timeline-item {
  position: relative;
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
}

/* Date */
.timeline-date {
  width: 30%;
  text-align: right;
  padding-right: 35px;
  font-weight: 700;
  font-size: 1.25rem;
  color: #aeddff;
}

/* Carte */
.timeline-content {
  width: 60%;
  background: #1f1f1f; /* plus clair que #1a1a1a */
  padding: 30px 32px;
  border-radius: 14px;
  border: 1px solid #4a4a4a;
  box-shadow: 0 0 22px rgba(95,179,255,0.25);
  color: #f2f2f2;
}

/* Titre de formation (ajout automatique si tu veux l’utiliser plus tard)
.timeline-title {
  font-size: 1.15rem;
  font-weight: 700;
  margin-bottom: 10px;
  color: #ffffff;
}
*/

/* Pastille */
.timeline-dot {
  position: absolute;
  left: 50%;
  top: 18px;
  width: 18px;
  height: 18px;
  background: #5fb3ff;
  border-radius: 50%;
  transform: translateX(-50%);
  border: 3px solid #0d0d0d;
}

/* Transition narrative */
.transition {
  margin-top: 18px;
  padding: 15px 20px;
  background: rgba(95,179,255,0.12);
  border-left: 4px solid #5fb3ff;
  border-radius: 4px;
  font-style: italic;
  color: #d8ecff;
  line-height: 1.55;
}

/* Tag compétence clé */
.skill-tag {
  display: inline-block;
  background: linear-gradient(90deg, #5fb3ff, #9cd8ff);
  color: #0d0d0d;
  font-weight: 600;
  padding: 5px 12px;
  border-radius: 6px;
  margin-bottom: 14px;
  font-size: 0.9rem;
  letter-spacing: 0.2px;
  box-shadow: 0 0 8px rgba(95,179,255,0.35);
}
</style>
