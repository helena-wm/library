<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Perpustakaan Helena — Prototype</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,400;0,9..144,600;0,9..144,700;1,9..144,500;1,9..144,600&family=Manrope:wght@400;500;600;700;800&display=swap" rel="stylesheet">
<style>
  :root{
    --ink:#12333F;
    --ink-deep:#0B252F;
    --teal:#1B5A73;
    --teal-soft:#e9f1f0;
    --paper:#FBF8F1;
    --card:#FFFEFA;
    --gold:#C9973E;
    --gold-deep:#A87A28;
    --gold-pale:#F3E4C4;
    --clay:#B5473B;
    --muted:#6B7D82;
    --text:#1E2E33;
    --radius:18px;
    --serif: 'Fraunces', Georgia, serif;
    --sans: 'Manrope', Arial, sans-serif;
  }
  *{box-sizing:border-box; margin:0; padding:0;}
  html, body{height:100%;}
  body{
    font-family: var(--sans);
    background:
      radial-gradient(circle at 20% 10%, #24444f 0%, transparent 45%),
      radial-gradient(circle at 80% 90%, #1a3540 0%, transparent 40%),
      #142c34;
    display:flex; justify-content:center; align-items:flex-start;
    min-height:100%;
    padding:28px 12px;
  }
  .phone{
    width:390px; max-width:100%;
    background:var(--paper);
    border-radius:40px;
    box-shadow:0 40px 80px rgba(6,20,26,0.5), 0 0 0 2px rgba(201,151,62,0.15);
    overflow:hidden;
    position:relative;
    border:10px solid var(--ink-deep);
    height:800px;
    display:flex;
    flex-direction:column;
  }
  .screen{
    display:none;
    flex-direction:column;
    height:100%;
    width:100%;
    position:relative;
    overflow:hidden;
    animation: rise .32s ease;
  }
  .screen.active{display:flex;}
  @keyframes rise{
    from{opacity:0; transform:translateY(10px);}
    to{opacity:1; transform:translateY(0);}
  }

  @media (max-width: 480px){
    body{padding:0; align-items:stretch; background:var(--paper);}
    .phone{
      width:100%;
      height:100dvh;
      border:none;
      border-radius:0;
      box-shadow:none;
    }
    .badgekit{display:none;}
  }

  .statusbar{
    height:26px; background:var(--ink-deep); color:#cfe0e6;
    font-size:11px; display:flex; align-items:center; justify-content:space-between;
    padding:0 18px; font-family: var(--sans);
  }

  /* header */
  .header{
    background: linear-gradient(160deg, var(--teal) 0%, var(--ink) 100%);
    color:#fff;
    padding:18px 20px 22px;
    position:relative;
  }
  .header::after{
    content:"";
    position:absolute; left:0; right:0; bottom:0; height:1px;
    background:linear-gradient(90deg, transparent, rgba(201,151,62,.55), transparent);
  }
  .header h1{font-family:var(--serif); font-size:19px; font-weight:600; letter-spacing:.2px;}
  .header p{font-size:12px; color:#bcd4de; margin-top:2px;}
  .header .back{
    position:absolute; left:16px; top:18px;
    width:30px; height:30px; border-radius:50%;
    background:rgba(255,255,255,.12);
    display:flex; align-items:center; justify-content:center;
    color:#fff; font-size:16px; cursor:pointer; border:none;
  }

  .content{flex:1; min-height:0; padding:18px 18px 96px; overflow-y:auto; -webkit-overflow-scrolling:touch;}

  /* auth screens */
  .auth-hero{
    background: linear-gradient(165deg, var(--teal) 0%, var(--ink-deep) 100%);
    color:#fff; padding:56px 28px 38px; text-align:center;
    border-radius:0 0 34px 34px;
    position:relative;
    overflow:hidden;
  }
  .auth-hero::before{
    content:"";
    position:absolute; inset:0;
    background:
      repeating-linear-gradient(90deg, rgba(255,255,255,.025) 0 2px, transparent 2px 26px);
    pointer-events:none;
  }
  .auth-hero .logo{
    width:66px;height:66px;border-radius:16px;
    background:linear-gradient(160deg, var(--gold) 0%, var(--gold-deep) 100%);
    display:flex;align-items:center;justify-content:center;margin:0 auto 16px;
    font-family:var(--serif); font-size:26px; color:var(--ink-deep); font-weight:700; font-style:italic;
    box-shadow:0 10px 22px rgba(0,0,0,.3), inset 0 1px 0 rgba(255,255,255,.35);
    position:relative; z-index:1;
  }
  .auth-hero h1{font-family:var(--serif); font-size:25px; font-weight:600; position:relative; z-index:1;}
  .auth-hero p{font-size:13px; color:#c7dde3; margin-top:8px; line-height:1.5; position:relative; z-index:1;}
  .auth-body{padding:26px 22px;}
  .field{margin-bottom:14px;}
  .field label{font-size:11.5px; color:var(--muted); font-weight:700; display:block; margin-bottom:6px; text-transform:uppercase; letter-spacing:.4px;}
  .field input, .field select{
    width:100%; padding:12px 14px; border-radius:12px; border:1.5px solid #e2dcc9;
    font-size:14px; background:var(--card); color:var(--text); font-family:var(--sans);
  }
  .field input:focus, .field select:focus{outline:none; border-color:var(--gold);}
  .btn{
    display:block; width:100%; text-align:center; padding:14px;
    border-radius:14px; border:none; font-size:14.5px; font-weight:700;
    cursor:pointer; transition:transform .12s ease, box-shadow .12s ease;
    font-family:var(--sans);
    -webkit-user-select:none; user-select:none;
  }
  .btn:active{transform:scale(.97);}
  .btn-primary{
    background:linear-gradient(160deg, var(--gold) 0%, var(--gold-deep) 100%);
    color:#241505;
    box-shadow:0 8px 18px rgba(169,122,32,.35), inset 0 1px 0 rgba(255,255,255,.3);
  }
  .btn-secondary{background:var(--teal-soft); color:var(--teal);}
  .btn-outline{background:#fff; color:var(--teal); border:1.5px solid var(--teal);}
  .btn-ghost{background:transparent; color:var(--teal); font-weight:700; padding:8px;}
  .link-row{text-align:center; margin-top:16px; font-size:13px; color:var(--muted);}
  .link-row a{color:var(--teal); font-weight:700; text-decoration:none; cursor:pointer;}

  .role-toggle{display:flex; gap:8px; background:var(--teal-soft); padding:4px; border-radius:12px;}
  .role-opt{
    flex:1; text-align:center; padding:9px 6px; border-radius:9px; font-size:12px; font-weight:700;
    color:var(--teal); cursor:pointer; transition:all .15s ease;
  }
  .role-opt.active{background:var(--ink-deep); color:var(--gold-pale); box-shadow:0 4px 10px rgba(18,51,63,.25);}

  .admin-entry{
    text-align:center; margin-top:20px; font-size:11.5px; font-weight:700; color:var(--muted);
    cursor:pointer; padding:10px; border-top:1px dashed #e2dcc9;
  }
  .admin-entry:hover{color:var(--ink);}
  .form-error{
    font-size:11.5px; color:var(--clay); background:#f8e2df; padding:9px 12px; border-radius:10px; margin-bottom:14px;
    display:none;
  }
  .form-error.show{display:block;}

  .admin-badge{
    display:inline-block; font-size:9.5px; font-weight:800; letter-spacing:.5px; text-transform:uppercase;
    background:var(--clay); color:#fff; padding:3px 9px; border-radius:20px; margin-left:6px; vertical-align:middle;
  }
  .admin-book-card{
    background:var(--card); border-radius:14px; padding:12px 14px; margin-bottom:10px;
    display:flex; gap:12px; align-items:center; box-shadow:0 2px 10px rgba(18,51,63,.06); border:1px solid #ece5d2;
  }
  .admin-book-card .meta{flex:1;}
  .admin-book-card .meta .title{font-size:13px; font-weight:700; font-family:var(--serif);}
  .admin-book-card .meta .sub{font-size:10.5px; color:var(--muted); margin-top:2px;}
  .admin-book-card .acts{display:flex; flex-direction:column; gap:6px;}
  .icon-btn{
    width:30px; height:30px; border-radius:9px; border:none; cursor:pointer; font-size:13px;
    display:flex; align-items:center; justify-content:center;
  }
  .icon-btn.edit{background:var(--teal-soft); color:var(--teal);}
  .icon-btn.del{background:#f8e2df; color:var(--clay);}
  .admin-stat{
    background:linear-gradient(160deg, var(--teal) 0%, var(--ink) 100%); border-radius:14px; padding:14px;
    color:#fff; flex:1; box-shadow:0 6px 16px rgba(18,51,63,.2);
  }
  .admin-stat .n{font-family:var(--serif); font-size:22px; font-weight:700; color:var(--gold-pale);}
  .admin-stat .l{font-size:10.5px; color:#cfe0e6; margin-top:2px;}

  /* dashboard */
  .greeting{font-size:12px; color:#bcd4de; font-family:var(--sans);}
  .greeting b{font-family:var(--serif); font-weight:600; color:#fff; font-size:18px; display:block; margin-top:3px;}
  .stat-row{display:flex; gap:10px; margin-top:16px;}
  .stat-card{
    flex:1; background:rgba(255,255,255,.13); border-radius:14px;
    padding:11px 12px; border:1px solid rgba(255,255,255,.1);
  }
  .stat-card .n{font-family:var(--serif); font-size:20px; font-weight:700; color:var(--gold-pale);}
  .stat-card .l{font-size:10.5px; color:#cfe0e6; margin-top:1px;}

  .section-title{
    font-family:var(--serif); font-size:15px; font-weight:600; color:var(--text);
    margin:8px 0 12px; display:flex; justify-content:space-between; align-items:center;
  }
  .section-title span.more{font-family:var(--sans); font-size:11px; color:var(--gold-deep); font-weight:700; cursor:pointer; text-transform:uppercase; letter-spacing:.3px;}

  .book-scroll{display:flex; gap:14px; overflow-x:auto; padding:2px 2px 8px; margin-bottom:22px;}
  .book-cover{
    min-width:106px; width:106px; cursor:pointer;
  }
  .cover-art{
    width:106px; height:150px; border-radius:6px 10px 10px 6px;
    display:flex; flex-direction:column; align-items:center; justify-content:flex-start;
    color:#fff; font-weight:700; font-size:22px; text-align:center;
    box-shadow:0 8px 18px rgba(18,51,63,.28), inset 3px 0 0 rgba(0,0,0,.18);
    position:relative; overflow:hidden; font-family:var(--serif); padding-top:16px;
  }
  .cover-art::after{
    content:attr(data-tag);
    position:absolute; left:0; right:0; bottom:0;
    background:rgba(0,0,0,.28); color:#f3e4c4; font-family:var(--sans);
    font-size:8px; letter-spacing:.5px; padding:4px 0; text-align:center; font-weight:700;
  }
  .book-cover .title{font-size:11.5px; font-weight:700; margin-top:9px; color:var(--text); line-height:1.3; font-family:var(--serif);}
  .book-cover .author{font-size:10.5px; color:var(--muted); font-style:italic;}

  .notif-card{
    background:var(--card); border-radius:14px; padding:13px 14px; margin-bottom:10px;
    display:flex; gap:12px; align-items:flex-start; box-shadow:0 2px 10px rgba(18,51,63,.07);
    border-left:3px solid var(--gold);
  }
  .notif-card .ic{font-size:18px;}
  .notif-card .t{font-size:12.5px; font-weight:700;}
  .notif-card .d{font-size:11px; color:var(--muted); margin-top:2px;}

  /* menu grid */
  .menu-grid{display:grid; grid-template-columns:1fr 1fr; gap:14px; margin-top:6px;}
  .menu-item{
    background:var(--card); border-radius:16px; padding:20px 14px;
    text-align:center; cursor:pointer;
    box-shadow:0 3px 12px rgba(18,51,63,.08);
    border:1.5px solid transparent;
    transition:border-color .15s ease;
  }
  .menu-item:active{border-color:var(--gold);}
  .menu-item .ic{
    width:46px; height:46px; border-radius:13px; background:var(--teal-soft);
    display:flex; align-items:center; justify-content:center; margin:0 auto 10px;
    font-size:20px;
  }
  .menu-item .t{font-size:12.5px; font-weight:700; color:var(--text); font-family:var(--serif);}
  .menu-item .d{font-size:10px; color:var(--muted); margin-top:4px; line-height:1.3;}

  /* search */
  .search-bar{
    display:flex; align-items:center; gap:8px; background:var(--card);
    border-radius:14px; padding:11px 14px; box-shadow:0 2px 8px rgba(18,51,63,.07);
    margin-bottom:16px; border:1px solid #ece5d2;
  }
  .search-bar input{border:none; outline:none; flex:1; font-size:13.5px; background:transparent; font-family:var(--sans);}
  .book-row{
    display:flex; gap:12px; background:var(--card); border-radius:14px; padding:12px;
    margin-bottom:10px; cursor:pointer; box-shadow:0 2px 10px rgba(18,51,63,.06);
  }
  .book-row .cover-art{width:56px; height:78px; border-radius:4px 8px 8px 4px; font-size:13px; padding-top:8px;}
  .book-row .cover-art::after{display:none;}
  .book-row .meta{flex:1;}
  .book-row .meta .title{font-size:13px; font-weight:700; color:var(--text); font-family:var(--serif);}
  .book-row .meta .author{font-size:11px; color:var(--muted); margin-top:2px; font-style:italic;}
  .badge{
    display:inline-block; font-size:10px; font-weight:700; padding:3px 8px;
    border-radius:20px; margin-top:6px;
  }
  .badge.ok{background:#e3f0e6; color:#2f7d43;}
  .badge.low{background:#f8ead2; color:#a3701d;}

  .tag-scroll{display:flex; gap:8px; overflow-x:auto; margin:0 0 14px; padding-bottom:2px;}
  .tag{font-size:10.5px; background:var(--teal-soft); color:var(--teal); padding:5px 12px; border-radius:20px; font-weight:700; white-space:nowrap;}
  .tag.active{background:var(--ink); color:#f3e4c4;}

  /* role toggle (login) */
  .role-toggle{display:flex; background:var(--teal-soft); border-radius:14px; padding:4px; margin-bottom:18px;}
  .role-toggle button{flex:1; border:none; background:transparent; padding:10px; border-radius:11px; font-size:12.5px; font-weight:700; color:var(--teal); cursor:pointer; font-family:var(--sans);}
  .role-toggle button.active{background:var(--ink); color:#f3e4c4; box-shadow:0 3px 10px rgba(18,51,63,.25);}

  /* admin */
  .admin-stat-grid{display:grid; grid-template-columns:1fr 1fr; gap:10px; margin-top:16px;}
  .admin-book-row{
    background:var(--card); border-radius:14px; padding:12px; margin-bottom:10px;
    display:flex; gap:12px; align-items:center; box-shadow:0 2px 10px rgba(18,51,63,.06); border:1px solid #ece5d2;
  }
  .admin-book-row .cover-mini{
    width:44px; height:60px; border-radius:3px 6px 6px 3px; display:flex; align-items:center; justify-content:center;
    color:#fff; font-family:var(--serif); font-weight:700; font-size:12px; flex-shrink:0;
  }
  .admin-book-row .meta{flex:1; min-width:0;}
  .admin-book-row .meta .title{font-size:12.5px; font-weight:700; font-family:var(--serif);}
  .admin-book-row .meta .sub{font-size:10.5px; color:var(--muted); margin-top:2px;}
  .admin-book-row .acts{display:flex; gap:6px; flex-shrink:0;}
  .icon-btn{
    width:32px; height:32px; border-radius:9px; border:none; background:var(--teal-soft);
    color:var(--teal); font-size:14px; display:flex; align-items:center; justify-content:center; cursor:pointer;
  }
  .icon-btn.danger{background:#f8e2df; color:var(--clay);}
  .fab{
    position:absolute; right:18px; bottom:100px; width:52px; height:52px; border-radius:50%;
    background:linear-gradient(160deg, var(--gold), var(--gold-deep)); color:#241505; font-size:24px;
    border:none; display:flex; align-items:center; justify-content:center;
    box-shadow:0 10px 22px rgba(169,122,32,.4); cursor:pointer; z-index:5;
  }
  .empty-hint{text-align:center; color:var(--muted); font-size:12.5px; padding:36px 10px; line-height:1.6;}

  /* detail buku */
  .detail-cover{
    width:150px; height:212px; border-radius:6px 12px 12px 6px; margin:6px auto 16px;
    display:flex; flex-direction:column; align-items:center; justify-content:flex-start; color:#fff;
    font-weight:700; font-size:32px; box-shadow:0 16px 30px rgba(18,51,63,.3), inset 4px 0 0 rgba(0,0,0,.2);
    font-family:var(--serif); padding-top:24px; position:relative; overflow:hidden;
  }
  .detail-cover .call-no{
    position:absolute; left:0; right:0; bottom:0; background:rgba(0,0,0,.3);
    color:#f3e4c4; font-family:var(--sans); font-size:9.5px; letter-spacing:.6px;
    padding:6px 0; text-align:center; font-weight:700;
  }
  .detail-title{font-family:var(--serif); font-size:19px; font-weight:600; text-align:center;}
  .detail-author{font-size:12.5px; color:var(--muted); text-align:center; margin-top:4px; font-style:italic;}
  .detail-tags{display:flex; gap:8px; justify-content:center; margin:14px 0; flex-wrap:wrap;}
  .detail-desc{font-size:13px; color:var(--text); line-height:1.7; margin:10px 0 20px;}
  .detail-actions{display:flex; flex-direction:column; gap:10px; margin-top:6px;}
  .stock-row{
    display:flex; justify-content:space-between; align-items:center;
    background:var(--card); border-radius:12px; padding:12px 14px; margin-bottom:16px;
    box-shadow:0 2px 8px rgba(18,51,63,.06); border:1px solid #ece5d2;
  }
  .stock-row .l{font-size:11.5px; color:var(--muted);}
  .stock-row .v{font-family:var(--serif); font-size:16px; font-weight:700; color:var(--teal);}

  /* form */
  .form-card{background:var(--card); border-radius:16px; padding:18px; box-shadow:0 3px 14px rgba(18,51,63,.08); border:1px solid #ece5d2;}
  textarea{width:100%; padding:12px 14px; border-radius:12px; border:1.5px solid #e2dcc9; font-size:13.5px; font-family:var(--sans); resize:none; background:var(--card);}

  /* ebook reader */
  .reader-page{
    background:
      linear-gradient(180deg, rgba(201,151,62,.06), transparent 40px),
      #fdf9ee;
    border-radius:10px; padding:22px 20px; font-size:13.5px; line-height:1.95; color:#2c2013;
    box-shadow:inset 0 0 0 1px #ecdfc0, 0 4px 16px rgba(18,51,63,.1); min-height:440px;
    font-family:var(--serif); position:relative;
  }
  .reader-page p{margin-bottom:14px;}
  .reader-page p:first-of-type::first-letter{
    font-size:2.5em; font-weight:700; float:left; line-height:0.85; padding-right:6px; padding-top:4px;
    color:var(--gold-deep);
  }
  .reader-toolbar{
    display:flex; justify-content:space-between; align-items:center;
    background:var(--ink-deep); color:#f3e4c4; padding:9px 14px; border-radius:12px; font-size:11px; margin-bottom:14px;
    font-family:var(--sans); font-weight:600;
  }
  .reader-toolbar span{cursor:pointer;}

  /* riwayat / favorit list */
  .history-card{
    background:var(--card); border-radius:14px; padding:13px 14px; margin-bottom:10px;
    box-shadow:0 2px 10px rgba(18,51,63,.06); display:flex; gap:12px; align-items:center; border:1px solid #ece5d2;
  }
  .history-card .cover-art{width:44px; height:62px; border-radius:3px 6px 6px 3px; font-size:11px; padding-top:6px;}
  .history-card .cover-art::after{display:none;}
  .history-card .meta{flex:1;}
  .history-card .meta .title{font-size:12.5px; font-weight:700; font-family:var(--serif);}
  .history-card .meta .sub{font-size:10.5px; color:var(--muted); margin-top:2px;}
  .status-pill{font-size:9.5px; font-weight:700; padding:3px 9px; border-radius:20px;}
  .status-pill.active{background:#e3f0e6; color:#2f7d43;}
  .status-pill.done{background:#eceeee; color:#607581;}
  .status-pill.late{background:#f8e2df; color:var(--clay);}

  /* profil */
  .profile-head{text-align:center; padding:32px 20px 22px;}
  .avatar{
    width:80px; height:80px; border-radius:50%;
    background:linear-gradient(160deg, var(--gold) 0%, var(--gold-deep) 100%);
    color:var(--ink-deep); font-weight:700; font-size:28px; font-family:var(--serif);
    display:flex; align-items:center; justify-content:center; margin:0 auto 12px;
    box-shadow:0 8px 20px rgba(0,0,0,.25), inset 0 1px 0 rgba(255,255,255,.3);
  }
  .profile-head h2{font-family:var(--serif); font-size:18px; font-weight:600; color:#fff;}
  .profile-head p{font-size:12px; color:#c7dde3; margin-top:3px;}
  .profile-list{background:var(--card); border-radius:14px; overflow:hidden; margin-bottom:14px; box-shadow:0 2px 10px rgba(18,51,63,.06); border:1px solid #ece5d2;}
  .profile-list .item{
    display:flex; justify-content:space-between; align-items:center;
    padding:14px 16px; font-size:13px; font-weight:600; color:var(--text);
    border-bottom:1px solid #f0ead9; cursor:pointer;
  }
  .profile-list .item:last-child{border-bottom:none;}
  .profile-list .item .arrow{color:var(--muted); font-size:13px;}

  /* bottom nav */
  .bottomnav{
    position:absolute; bottom:0; left:0; right:0;
    background:var(--card); display:flex; justify-content:space-around;
    padding:10px 6px 14px; box-shadow:0 -6px 18px rgba(18,51,63,.1);
    border-radius:24px 24px 0 0; border-top:1px solid #f0ead9;
  }
  .navitem{
    flex:1; text-align:center; cursor:pointer; color:var(--muted);
    display:flex; flex-direction:column; align-items:center; gap:3px;
    font-size:10px; font-weight:700; padding:4px; position:relative;
  }
  .navitem .ic{font-size:19px;}
  .navitem.active{color:var(--teal);}
  .navitem.active .ic{color:var(--gold-deep);}
  .navitem.active::before{
    content:""; position:absolute; top:-2px; width:16px; height:2px; border-radius:2px;
    background:var(--gold);
  }

  .toast{
    position:absolute; bottom:104px; left:20px; right:20px;
    background:var(--ink-deep); color:#f3e4c4; padding:12px 16px; border-radius:12px;
    font-size:12.5px; text-align:center; opacity:0; pointer-events:none;
    transition:opacity .25s ease, transform .25s ease; transform:translateY(8px);
    z-index:50; font-weight:600;
  }
  .toast.show{opacity:1; transform:translateY(0);}

  .badgekit{position:fixed; top:16px; right:16px; background:var(--ink-deep); color:var(--gold); font-size:11px; padding:8px 12px; border-radius:20px; font-weight:700; box-shadow:0 6px 16px rgba(0,0,0,.3); font-family:var(--sans);}
</style>
</head>
<body>

<div class="badgekit">Mode Prototype</div>

<div class="phone" id="phone">

  <!-- ===================== LOGIN ===================== -->
  <div class="screen active" id="screen-login">
    <div class="auth-hero">
      <div class="logo">PH</div>
      <h1>Perpustakaan Helena</h1>
      <p>Cari, pinjam, dan baca koleksi buku perpustakaan kapan saja, di mana saja.</p>
    </div>
    <div class="auth-body">
      <div class="field">
        <label>Email / NIM</label>
        <input type="text" id="login-id" name="login-id-field" autocapitalize="off" autocorrect="off" spellcheck="false" autocomplete="off">
      </div>
      <div class="field">
        <label>Kata Sandi</label>
        <input type="password" id="login-pass" name="login-pass-field" autocomplete="new-password">
      </div>
      <button class="btn btn-primary"
              id="btn-masuk"
              onclick="doLogin()">Masuk</button>
      <div class="link-row">Belum punya akun? <a onclick="go('register')">Daftar sekarang</a></div>
    </div>
  </div>

  <!-- ===================== REGISTER ===================== -->
  <div class="screen" id="screen-register">
    <div class="header">
      <button class="back" onclick="go('login')">←</button>
      <h1 style="text-align:center;">Buat Akun Baru</h1>
    </div>
    <div class="content">
      <div class="form-error" id="reg-error"></div>
      <div class="field"><label>Nama Lengkap</label><input type="text" id="reg-name" placeholder="Nama lengkap Anda" autocomplete="off"></div>
      <div class="field"><label>NIM</label><input type="text" id="reg-nim" placeholder="Contoh: 1025720124" autocomplete="off"></div>
      <div class="field"><label>Email</label><input type="text" id="reg-email" placeholder="nama@kampus.ac.id" autocapitalize="off" autocorrect="off" spellcheck="false" autocomplete="off"></div>
      <div class="field"><label>Status</label>
        <select id="reg-status"><option>Mahasiswa</option><option>Dosen</option><option>Tenaga Kependidikan</option></select>
      </div>
      <div class="field"><label>Kata Sandi</label><input type="password" id="reg-pass" placeholder="Buat kata sandi (min. 6 karakter)" autocomplete="off"></div>
      <button class="btn btn-primary" onclick="doRegister()">Daftar</button>
      <div class="link-row">Sudah punya akun? <a onclick="go('login')">Masuk</a></div>
    </div>
  </div>

  <!-- ===================== DASHBOARD ADMIN ===================== -->
  <div class="screen" id="screen-admin-dashboard">
    <div class="header" style="padding-bottom:18px;">
      <div class="greeting">Panel Administrator<b id="admin-greet-name">Admin Perpustakaan 🛠️</b></div>
      <div class="stat-row">
        <div class="admin-stat"><div class="n" id="admin-total-buku">5</div><div class="l">Total Judul Buku</div></div>
        <div class="admin-stat"><div class="n" id="admin-total-user">3</div><div class="l">Pengguna Terdaftar</div></div>
        <div class="admin-stat"><div class="n" id="admin-total-pinjam">2</div><div class="l">Sedang Dipinjam</div></div>
      </div>
    </div>
    <div class="content">
      <div class="section-title">Menu Admin</div>
      <div class="menu-grid">
        <div class="menu-item" onclick="go('admin-buku')"><div class="ic">📚</div><div class="t">Kelola Buku</div><div class="d">Tambah, ubah, hapus judul</div></div>
        <div class="menu-item" onclick="go('admin-tambah')"><div class="ic">➕</div><div class="t">Tambah Buku</div><div class="d">Input judul baru ke koleksi</div></div>
        <div class="menu-item" onclick="go('admin-user')"><div class="ic">👥</div><div class="t">Kelola Pengguna</div><div class="d">Data akun terdaftar</div></div>
        <div class="menu-item" onclick="go('admin-pinjam')"><div class="ic">🔄</div><div class="t">Peminjaman Aktif</div><div class="d">Pantau status pinjam</div></div>
      </div>
      <div class="section-title" style="margin-top:18px;">Koleksi Terbaru</div>
      <div id="admin-recent-books"></div>
    </div>
    <div class="bottomnav">
      <div class="navitem active"><div class="ic">🏠</div>Beranda</div>
      <div class="navitem" onclick="go('admin-buku')"><div class="ic">📚</div>Buku</div>
      <div class="navitem" onclick="go('admin-user')"><div class="ic">👥</div>Pengguna</div>
      <div class="navitem" onclick="go('admin-profil')"><div class="ic">🛠️</div>Akun</div>
    </div>
  </div>

  <!-- ===================== ADMIN: KELOLA BUKU ===================== -->
  <div class="screen" id="screen-admin-buku">
    <div class="header"><button class="back" onclick="go('admin-dashboard')">←</button><h1 style="text-align:center;">Kelola Buku <span class="admin-badge">Admin</span></h1></div>
    <div class="content">
      <button class="btn btn-primary" style="margin-bottom:16px;" onclick="go('admin-tambah')">➕ Tambah Buku Baru</button>
      <div id="admin-book-list"></div>
    </div>
    <button class="fab" onclick="go('admin-tambah')" title="Tambah buku baru">➕</button>
  </div>

  <!-- ===================== ADMIN: TAMBAH / EDIT BUKU ===================== -->
  <div class="screen" id="screen-admin-tambah">
    <div class="header"><button class="back" onclick="go('admin-buku')">←</button><h1 style="text-align:center;" id="admin-form-title">Tambah Buku Baru</h1></div>
    <div class="content">
      <div class="form-card">
        <div class="field"><label>Judul Buku</label><input type="text" id="af-title" placeholder="Contoh: Negeri 5 Menara"></div>
        <div class="field"><label>Penulis</label><input type="text" id="af-author" placeholder="Contoh: Ahmad Fuadi"></div>
        <div class="field"><label>Kategori</label>
          <select id="af-tag">
            <option>Fiksi Sejarah</option>
            <option>Sastra Klasik</option>
            <option>Non-Fiksi</option>
            <option>Sains Populer</option>
            <option>Ekonomi</option>
            <option>Pendidikan</option>
          </select>
        </div>
        <div class="field"><label>Nomor Panggil (Call Number)</label><input type="text" id="af-callno" placeholder="Contoh: 813 FUA"></div>
        <div class="field"><label>Jumlah Eksemplar</label><input type="number" id="af-stock" min="0" value="1"></div>
        <div class="field"><label>Sinopsis Singkat</label><textarea id="af-desc" rows="3" placeholder="Ringkasan singkat isi buku..."></textarea></div>
        <input type="hidden" id="af-editkey" value="">
        <button class="btn btn-primary" onclick="saveBook()">💾 Simpan Buku</button>
      </div>
    </div>
  </div>

  <!-- ===================== ADMIN: KELOLA PENGGUNA ===================== -->
  <div class="screen" id="screen-admin-user">
    <div class="header"><button class="back" onclick="go('admin-dashboard')">←</button><h1 style="text-align:center;">Pengguna Terdaftar <span class="admin-badge">Admin</span></h1></div>
    <div class="content">
      <div class="history-card">
        <div class="avatar" style="width:44px;height:44px;font-size:15px;">MH</div>
        <div class="meta"><div class="title">Maria Helena Waoma</div><div class="sub">NIM 1025720124 · 2 buku dipinjam</div></div>
        <span class="status-pill active">Aktif</span>
      </div>
      <div class="history-card">
        <div class="avatar" style="width:44px;height:44px;font-size:15px; background:linear-gradient(160deg,#6B7D82,#3c4c50);">RA</div>
        <div class="meta"><div class="title">Rendi Ardiansyah</div><div class="sub">NIM 1025720098 · 1 buku dipinjam</div></div>
        <span class="status-pill active">Aktif</span>
      </div>
      <div class="history-card">
        <div class="avatar" style="width:44px;height:44px;font-size:15px; background:linear-gradient(160deg,#8a5a3b,#4a2f1c);">SN</div>
        <div class="meta"><div class="title">Siti Nurhaliza</div><div class="sub">NIM 1025720056 · Tidak ada pinjaman</div></div>
        <span class="status-pill done">Non-aktif</span>
      </div>
      <div class="notif-card" style="margin-top:16px;">
        <div class="ic">🔒</div>
        <div><div class="t">Privasi data pengguna</div><div class="d">Admin hanya melihat status peminjaman, bukan riwayat bacaan atau favorit pribadi tiap pengguna.</div></div>
      </div>
    </div>
  </div>

  <!-- ===================== ADMIN: PEMINJAMAN AKTIF ===================== -->
  <div class="screen" id="screen-admin-pinjam">
    <div class="header"><button class="back" onclick="go('admin-dashboard')">←</button><h1 style="text-align:center;">Peminjaman Aktif <span class="admin-badge">Admin</span></h1></div>
    <div class="content">
      <div class="history-card">
        <div class="cover-art" style="background:linear-gradient(160deg,#1B5A73,#123a4a);">LB</div>
        <div class="meta"><div class="title">Laut Bercerita</div><div class="sub">Dipinjam oleh Maria Helena Waoma</div></div>
        <span class="status-pill active">Dipinjam</span>
      </div>
      <div class="history-card">
        <div class="cover-art" style="background:linear-gradient(160deg,#C9973E,#8c6420);">BM</div>
        <div class="meta"><div class="title">Bumi Manusia</div><div class="sub">Dipinjam oleh Maria Helena Waoma</div></div>
        <span class="status-pill late">Jatuh Tempo</span>
      </div>
      <div class="history-card">
        <div class="cover-art" style="background:linear-gradient(160deg,#6B7D82,#3c4c50);">FT</div>
        <div class="meta"><div class="title">Filosofi Teras</div><div class="sub">Dipinjam oleh Rendi Ardiansyah</div></div>
        <span class="status-pill active">Dipinjam</span>
      </div>
    </div>
  </div>

  <!-- ===================== ADMIN: PROFIL/AKUN ===================== -->
  <div class="screen" id="screen-admin-profil">
    <div class="header profile-head">
      <div class="avatar" style="background:linear-gradient(160deg,#B5473B,#7a2e26);">A</div>
      <h2>Admin Perpustakaan</h2>
      <p>admin@perpushelena.ac.id · Akun Administrator</p>
    </div>
    <div class="content">
      <div class="profile-list">
        <div class="item" onclick="go('admin-buku')">Kelola Buku <span class="arrow">›</span></div>
        <div class="item" onclick="go('admin-user')">Kelola Pengguna <span class="arrow">›</span></div>
        <div class="item" onclick="go('admin-pinjam')">Peminjaman Aktif <span class="arrow">›</span></div>
        <div class="item" onclick="toast('Fitur pengaturan akun admin')">Pengaturan Akun <span class="arrow">›</span></div>
      </div>
      <button class="btn btn-outline" style="color:var(--clay); border-color:var(--clay);" onclick="doLogout()">Keluar (Logout)</button>
    </div>
    <div class="bottomnav">
      <div class="navitem" onclick="go('admin-dashboard')"><div class="ic">🏠</div>Beranda</div>
      <div class="navitem" onclick="go('admin-buku')"><div class="ic">📚</div>Buku</div>
      <div class="navitem" onclick="go('admin-user')"><div class="ic">👥</div>Pengguna</div>
      <div class="navitem active"><div class="ic">🛠️</div>Akun</div>
    </div>
  </div>

  <!-- ===================== DASHBOARD ===================== -->
  <div class="screen" id="screen-dashboard">
    <div class="header" style="padding-bottom:18px;">
      <div class="greeting">Selamat datang kembali,<b>Helena 👋</b></div>
      <div class="stat-row">
        <div class="stat-card"><div class="n">2</div><div class="l">Sedang Dipinjam</div></div>
        <div class="stat-card"><div class="n">1</div><div class="l">Jatuh Tempo</div></div>
        <div class="stat-card"><div class="n">5</div><div class="l">Rak Favorit</div></div>
      </div>
    </div>
    <div class="content">
      <div class="section-title">Pengingat Pengembalian <span class="more" onclick="go('notifikasi')">Lihat semua</span></div>
      <div class="notif-card">
        <div class="ic">⏰</div>
        <div>
          <div class="t">"Laut Bercerita" jatuh tempo 2 hari lagi</div>
          <div class="d">Kembalikan sebelum 06 Juli 2026 untuk hindari denda</div>
        </div>
      </div>

      <div class="section-title">Rekomendasi Untukmu <span class="more" onclick="go('cari')">Lihat semua</span></div>
      <div class="book-scroll">
        <div class="book-cover" onclick="openBook('laut')">
          <div class="cover-art" data-tag="813.086 CHU" style="background:linear-gradient(160deg,#1B5A73,#123a4a);">LB</div>
          <div class="title">Laut Bercerita</div>
          <div class="author">Leila S. Chudori</div>
        </div>
        <div class="book-cover" onclick="openBook('bumi')">
          <div class="cover-art" data-tag="899.221 TOE" style="background:linear-gradient(160deg,#C9973E,#8c6420);">BM</div>
          <div class="title">Bumi Manusia</div>
          <div class="author">Pramoedya A.T.</div>
        </div>
        <div class="book-cover" onclick="openBook('filosofi')">
          <div class="cover-art" data-tag="188 MAN" style="background:linear-gradient(160deg,#6B7D82,#3c4c50);">FT</div>
          <div class="title">Filosofi Teras</div>
          <div class="author">Henry Manampiring</div>
        </div>
      </div>

      <div class="section-title">Menu Utama</div>
      <div class="menu-grid">
        <div class="menu-item" onclick="go('cari')"><div class="ic">🔍</div><div class="t">Cari Buku</div></div>
        <div class="menu-item" onclick="openBook('laut')"><div class="ic">📖</div><div class="t">Pinjam Buku</div></div>
        <div class="menu-item" onclick="openEbook()"><div class="ic">📱</div><div class="t">Baca E-Book</div></div>
        <div class="menu-item" onclick="go('riwayat')"><div class="ic">🕒</div><div class="t">Riwayat</div></div>
        <div class="menu-item" onclick="go('favorit')"><div class="ic">⭐</div><div class="t">Rak Favorit</div></div>
        <div class="menu-item" onclick="go('notifikasi')"><div class="ic">🔔</div><div class="t">Notifikasi</div></div>
      </div>
    </div>
    <div class="bottomnav">
      <div class="navitem active"><div class="ic">🏠</div>Beranda</div>
      <div class="navitem" onclick="go('cari')"><div class="ic">🔍</div>Cari</div>
      <div class="navitem" onclick="go('menu')"><div class="ic">▦</div>Menu</div>
      <div class="navitem" onclick="go('profil')"><div class="ic">👤</div>Profil</div>
    </div>
  </div>

  <!-- ===================== MENU UTAMA ===================== -->
  <div class="screen" id="screen-menu">
    <div class="header"><button class="back" onclick="go('dashboard')">←</button><h1 style="text-align:center;">Menu Utama</h1></div>
    <div class="content">
      <div class="menu-grid">
        <div class="menu-item" onclick="go('cari')"><div class="ic">🔍</div><div class="t">Cari Buku</div><div class="d">Cari judul, penulis, kategori</div></div>
        <div class="menu-item" onclick="openBook('laut')"><div class="ic">📖</div><div class="t">Pinjam Buku</div><div class="d">Ajukan peminjaman fisik</div></div>
        <div class="menu-item" onclick="openEbook()"><div class="ic">📱</div><div class="t">Baca E-Book</div><div class="d">Baca versi digital</div></div>
        <div class="menu-item" onclick="go('riwayat')"><div class="ic">🕒</div><div class="t">Riwayat Peminjaman</div><div class="d">Daftar pinjam & kembali</div></div>
        <div class="menu-item" onclick="go('favorit')"><div class="ic">⭐</div><div class="t">Rak Favorit</div><div class="d">Buku yang disimpan</div></div>
        <div class="menu-item" onclick="go('notifikasi')"><div class="ic">🔔</div><div class="t">Notifikasi Pengembalian</div><div class="d">Pengingat jatuh tempo</div></div>
      </div>
    </div>
    <div class="bottomnav">
      <div class="navitem" onclick="go('dashboard')"><div class="ic">🏠</div>Beranda</div>
      <div class="navitem" onclick="go('cari')"><div class="ic">🔍</div>Cari</div>
      <div class="navitem active"><div class="ic">▦</div>Menu</div>
      <div class="navitem" onclick="go('profil')"><div class="ic">👤</div>Profil</div>
    </div>
  </div>

  <!-- ===================== CARI BUKU ===================== -->
  <div class="screen" id="screen-cari">
    <div class="header"><button class="back" onclick="go('dashboard')">←</button><h1 style="text-align:center;">Cari Buku</h1></div>
    <div class="content">
      <div class="search-bar">🔍<input type="text" placeholder="Judul, penulis, atau kategori..." value="Laut Bercerita"></div>
      <div class="tag-scroll">
        <span class="tag active">Semua</span>
        <span class="tag">Fiksi Sejarah</span>
        <span class="tag">Sastra Klasik</span>
        <span class="tag">Non-Fiksi</span>
        <span class="tag">Sains Populer</span>
        <span class="tag">Ekonomi</span>
      </div>
      <!-- Daftar buku dirender secara dinamis dari katalog yang dikelola admin -->
    </div>
    <div class="bottomnav">
      <div class="navitem" onclick="go('dashboard')"><div class="ic">🏠</div>Beranda</div>
      <div class="navitem active"><div class="ic">🔍</div>Cari</div>
      <div class="navitem" onclick="go('menu')"><div class="ic">▦</div>Menu</div>
      <div class="navitem" onclick="go('profil')"><div class="ic">👤</div>Profil</div>
    </div>
  </div>

  <!-- ===================== DETAIL BUKU ===================== -->
  <div class="screen" id="screen-detail">
    <div class="header"><button class="back" onclick="go('cari')">←</button><h1 style="text-align:center;">Detail Buku</h1></div>
    <div class="content">
      <div class="detail-cover" id="detail-cover" style="background:linear-gradient(160deg,#1B5A73,#123a4a);">
        <span id="detail-code">LB</span>
        <span class="call-no" id="detail-callno">813.086 CHU</span>
      </div>
      <div class="detail-title" id="detail-title">Laut Bercerita</div>
      <div class="detail-author" id="detail-author">Leila S. Chudori</div>
      <div class="detail-tags" id="detail-tags"><span class="tag">Fiksi Sejarah</span><span class="tag">Indonesia</span></div>
      <div class="stock-row"><div class="l">Ketersediaan stok fisik</div><div class="v" id="detail-stock">3 eksemplar</div></div>
      <div class="detail-desc" id="detail-desc">Novel yang mengisahkan perjuangan aktivis mahasiswa pada masa kelam sejarah Indonesia, dituturkan dengan sudut pandang yang menyentuh dan penuh empati.</div>
      <div class="detail-actions">
        <button class="btn btn-primary" onclick="go('pinjam')">📖 Pinjam Buku</button>
        <button class="btn btn-secondary" onclick="openEbook()">📱 Baca E-Book</button>
      </div>
    </div>
  </div>

  <!-- ===================== FORM PINJAM ===================== -->
  <div class="screen" id="screen-pinjam">
    <div class="header"><button class="back" onclick="go('detail')">←</button><h1 style="text-align:center;">Form Peminjaman</h1></div>
    <div class="content">
      <div class="form-card">
        <div class="field"><label>Judul Buku</label><input type="text" value="Laut Bercerita" readonly></div>
        <div class="field"><label>Nama Peminjam</label><input type="text" value="Maria Helena Waoma" readonly></div>
        <div class="field"><label>Tanggal Pinjam</label><input type="text" value="04 Juli 2026" readonly></div>
        <div class="field"><label>Tanggal Kembali (maks. 7 hari)</label><input type="text" value="11 Juli 2026" readonly></div>
        <div class="field"><label>Catatan (opsional)</label><textarea rows="3" placeholder="Contoh: ambil di rak referensi lantai 2"></textarea></div>
        <button class="btn btn-primary" onclick="toast('Peminjaman berhasil diajukan'); go('riwayat')">Konfirmasi Peminjaman</button>
      </div>
    </div>
  </div>

  <!-- ===================== BACA E-BOOK ===================== -->
  <div class="screen" id="screen-ebook">
    <div class="header"><button class="back" onclick="go('detail')">←</button><h1 style="text-align:center;" id="ebook-header-title">Baca E-Book</h1></div>
    <div class="content">
      <div class="reader-toolbar">
        <span onclick="changeFontSize()">Aa <span id="font-size-label">Sedang</span></span>
        <span id="reader-page-count">Hal. 1 / 5</span>
        <span id="reader-fav" onclick="toggleFavoriteReader()">☆ Favorit</span>
      </div>
      <div class="reader-page" id="reader-page-text" style="font-size:13.5px;">
        Memuat halaman...
      </div>
      <div style="display:flex; justify-content:space-between; margin-top:14px;">
        <button class="btn btn-outline" style="width:48%;" onclick="turnPage(-1)">← Sebelumnya</button>
        <button class="btn btn-primary" style="width:48%;" onclick="turnPage(1)">Berikutnya →</button>
      </div>
    </div>
  </div>

  <!-- ===================== RIWAYAT ===================== -->
  <div class="screen" id="screen-riwayat">
    <div class="header"><button class="back" onclick="go('dashboard')">←</button><h1 style="text-align:center;">Riwayat Peminjaman</h1></div>
    <div class="content">
      <div class="history-card">
        <div class="cover-art" style="background:linear-gradient(160deg,#1B5A73,#123a4a);">LB</div>
        <div class="meta"><div class="title">Laut Bercerita</div><div class="sub">Dipinjam 04 Jul — Kembali 11 Jul 2026</div></div>
        <span class="status-pill active">Dipinjam</span>
      </div>
      <div class="history-card">
        <div class="cover-art" style="background:linear-gradient(160deg,#C9973E,#8c6420);">BM</div>
        <div class="meta"><div class="title">Bumi Manusia</div><div class="sub">Dipinjam 28 Jun — Kembali 05 Jul 2026</div></div>
        <span class="status-pill late">Jatuh Tempo</span>
      </div>
      <div class="history-card">
        <div class="cover-art" style="background:linear-gradient(160deg,#6B7D82,#3c4c50);">FT</div>
        <div class="meta"><div class="title">Filosofi Teras</div><div class="sub">Dipinjam 10 Jun — Dikembalikan 17 Jun 2026</div></div>
        <span class="status-pill done">Selesai</span>
      </div>
    </div>
  </div>

  <!-- ===================== RAK FAVORIT ===================== -->
  <div class="screen" id="screen-favorit">
    <div class="header"><button class="back" onclick="go('dashboard')">←</button><h1 style="text-align:center;">Rak Favorit</h1></div>
    <div class="content">
      <div class="book-row" onclick="openBook('filosofi')">
        <div class="cover-art" style="background:linear-gradient(160deg,#6B7D82,#3c4c50);">FT</div>
        <div class="meta"><div class="title">Filosofi Teras</div><div class="author">Henry Manampiring</div><span class="badge low">Sisa 1 eksemplar</span></div>
      </div>
      <div class="book-row" onclick="openBook('bumi')">
        <div class="cover-art" style="background:linear-gradient(160deg,#C9973E,#8c6420);">BM</div>
        <div class="meta"><div class="title">Bumi Manusia</div><div class="author">Pramoedya A.T.</div><span class="badge ok">Tersedia · 2 eksemplar</span></div>
      </div>
    </div>
  </div>

  <!-- ===================== NOTIFIKASI ===================== -->
  <div class="screen" id="screen-notifikasi">
    <div class="header"><button class="back" onclick="go('dashboard')">←</button><h1 style="text-align:center;">Notifikasi Pengembalian</h1></div>
    <div class="content">
      <div class="notif-card"><div class="ic">⏰</div><div><div class="t">"Bumi Manusia" jatuh tempo besok</div><div class="d">Kembalikan sebelum 05 Juli 2026 agar terhindar dari denda</div></div></div>
      <div class="notif-card"><div class="ic">📚</div><div><div class="t">"Laut Bercerita" jatuh tempo 2 hari lagi</div><div class="d">Batas pengembalian 11 Juli 2026</div></div></div>
      <div class="notif-card"><div class="ic">✅</div><div><div class="t">Pengembalian "Filosofi Teras" berhasil dicatat</div><div class="d">Terima kasih telah mengembalikan tepat waktu</div></div></div>
    </div>
  </div>

  <!-- ===================== PROFIL ===================== -->
  <div class="screen" id="screen-profil">
    <div class="header profile-head">
      <div class="avatar">MH</div>
      <h2>Maria Helena Waoma</h2>
      <p>NIM 1025720124 · Mahasiswa Sistem Informasi</p>
    </div>
    <div class="content">
      <div class="profile-list">
        <div class="item" onclick="go('riwayat')">Riwayat Peminjaman <span class="arrow">›</span></div>
        <div class="item" onclick="go('favorit')">Rak Favorit <span class="arrow">›</span></div>
        <div class="item" onclick="go('notifikasi')">Notifikasi Pengembalian <span class="arrow">›</span></div>
        <div class="item" onclick="toast('Fitur pengaturan akun')">Pengaturan Akun <span class="arrow">›</span></div>
        <div class="item" onclick="toast('Menghubungkan ke pusat bantuan')">Pusat Bantuan <span class="arrow">›</span></div>
      </div>
      <button class="btn btn-outline" style="color:var(--clay); border-color:var(--clay);" onclick="doLogout()">Keluar (Logout)</button>
    </div>
    <div class="bottomnav">
      <div class="navitem" onclick="go('dashboard')"><div class="ic">🏠</div>Beranda</div>
      <div class="navitem" onclick="go('cari')"><div class="ic">🔍</div>Cari</div>
      <div class="navitem" onclick="go('menu')"><div class="ic">▦</div>Menu</div>
      <div class="navitem active"><div class="ic">👤</div>Profil</div>
    </div>
  </div>

  <div class="toast" id="toast"></div>
</div>

<script>
  // Konten simulasi halaman e-book (narasi original untuk keperluan prototype, bukan kutipan dari buku asli).
  // Setiap halaman berisi beberapa paragraf agar terasa seperti membaca bab sungguhan.
  const ebookContent = {
    laut:[
`Bab 1 — Pelabuhan Kecil

Malam itu, ombak menghantam karang dengan ritme yang seolah menghitung waktu. Biru Laut menatap ke kejauhan, mengingat janji yang belum sempat ia tepati kepada kawan-kawannya di kampus, tentang selebaran yang harus disebar sebelum subuh dan tentang pertemuan rahasia yang selalu berpindah tempat.

Ia menutup buku catatannya, menyadari bahwa perjuangan yang sesungguhnya baru saja dimulai. Angin laut membawa aroma garam dan kenangan yang tak pernah benar-benar pergi, mengingatkannya pada dapur ibunya yang selalu ramai setiap kali keluarga besar berkumpul.

Di sudut warung kopi, seorang kawan lama menyambutnya dengan senyum getir. "Kita harus lebih hati-hati sekarang," katanya pelan, sembari melirik ke arah pintu yang berkali-kali terbuka oleh orang-orang asing.`,

`Bab 2 — Surat yang Tak Terkirim

Di ruang kerja yang temaram, ia menulis surat untuk adiknya. Setiap kalimat terasa berat, seolah kertas itu menanggung seluruh rindu yang tertunda bertahun-tahun, tentang meja makan yang kini terasa lebih sepi, tentang kursi kosong yang tak seorang pun berani mengisinya.

Ia berhenti sejenak, memandangi foto lama di meja. Wajah-wajah itu tersenyum, tanpa tahu apa yang akan menimpa mereka di kemudian hari — sebuah masa ketika tawa bisa berubah menjadi ketakutan hanya dalam hitungan malam.

Ia melipat surat itu tanpa pernah mengirimkannya, menyimpannya di antara halaman-halaman buku yang paling jarang disentuh, seakan berharap suatu hari nanti seseorang akan menemukannya dan mengerti.`,

`Bab 3 — Kembali ke Kota

Kereta melaju pelan memasuki stasiun. Ia menghela napas panjang, siap menghadapi kenyataan yang selama ini ia hindari: kota yang sama, jalanan yang sama, namun dengan wajah-wajah yang kini menyimpan kecurigaan di balik senyum ramah mereka.

Di peron yang ramai, ia mencari sosok yang telah lama tak ia jumpai. Setiap wajah asing terasa seperti bayangan dari masa lalu yang enggan menghilang, dan setiap langkah kaki di belakangnya membuat jantungnya berdegup lebih cepat.

Seorang pedagang kaki lima menyapanya seakan tak terjadi apa-apa, dan untuk sesaat ia merasa dunia mungkin masih menyisakan tempat yang aman baginya.`,

`Bab 4 — Rumah Lama

Pintu kayu itu masih berderit seperti dulu. Ia melangkah masuk perlahan, membiarkan ingatan-ingatan lama menyeruak satu demi satu: suara piring beradu di dapur, tawa adik-adiknya saat berebut kursi paling dekat dengan televisi.

Di ruang tengah, sebuah meja makan kosong mengingatkannya pada percakapan-percakapan yang dulu memenuhi rumah itu dengan tawa dan perdebatan tentang politik, tentang cita-cita, tentang negeri yang mereka cintai dengan cara masing-masing.

Ia duduk di kursi ayahnya yang biasa, merasakan kehangatan kayu tua itu, dan untuk pertama kalinya sejak kepergiannya, ia membiarkan dirinya menangis tanpa perlu menyembunyikan wajah.`,

`Bab 5 — Pertemuan

Akhirnya ia bertemu dengan sahabat lama yang selama ini dicarinya. Mereka duduk berhadapan, saling menimbang kata sebelum memulai percakapan yang tertunda bertahun-tahun, seolah setiap kalimat harus dipilih dengan hati-hati agar tidak membuka luka yang belum sepenuhnya sembuh.

"Kau masih menulis?" tanya sahabatnya sambil menyodorkan segelas teh hangat. Ia mengangguk pelan, menyadari bahwa menulis adalah satu-satunya cara yang tersisa baginya untuk tetap merasa hidup di tengah dunia yang begitu ingin membungkamnya.

Di akhir percakapan, ada kelegaan yang tak terucap. Laut di kejauhan tetap bergemuruh, seolah menjadi saksi bahwa cerita ini akhirnya menemukan tempatnya untuk berhenti sejenak, meski luka sejarah itu tak pernah benar-benar mengering.`,

`Bab 6 — Yang Tertinggal

Bertahun-tahun kemudian, seorang perempuan muda membuka kotak kayu peninggalan pamannya. Di dalamnya ia menemukan surat-surat lama, foto-foto yang mulai menguning, dan sebuah buku catatan penuh coretan tentang laut, tentang kebebasan, tentang kawan-kawan yang tak pernah kembali.

Ia membaca satu per satu, mencoba menyusun kembali kepingan cerita yang selama ini hanya ia dengar sepotong-sepotong dari orang tuanya. Setiap kalimat terasa seperti jendela kecil menuju masa yang tak pernah benar-benar ia alami, namun kini terasa begitu dekat.

Di halaman terakhir buku itu tertulis satu kalimat sederhana: "Jika suatu hari kau membaca ini, ingatlah bahwa laut selalu punya cara untuk bercerita, bahkan ketika suara-suara yang lain telah dibungkam."`
    ],
    bumi:[
`Bab 1 — Wonokromo

Minke duduk di beranda rumah, memandangi jalanan yang basah oleh hujan sore. Pikirannya melayang pada pelajaran yang baru saja ia terima di sekolah H.B.S., tentang bangsa-bangsa Eropa yang dianggap sebagai puncak peradaban, sebuah gagasan yang mulai terasa ganjil di benaknya sendiri.

Ia mulai menuliskan gagasannya di buku catatan, sebuah kebiasaan yang kelak akan membentuk caranya memandang dunia dan bangsanya sendiri. Setiap goresan pena terasa seperti langkah kecil menuju sesuatu yang belum ia pahami sepenuhnya.

Ibunya memanggil dari dalam rumah, mengingatkannya bahwa waktu makan malam sudah tiba, namun pikirannya masih tertinggal di antara baris-baris tulisan yang belum selesai.`,

`Bab 2 — Perjumpaan

Di rumah besar itu, ia bertemu dengan seorang gadis yang caranya berbicara begitu berbeda dari yang pernah ia kenal sebelumnya — lugas, berani, dan penuh keyakinan meski usianya masih sangat muda.

Percakapan mereka mengalir tentang keadilan, tentang bangsa, tentang mimpi-mimpi yang sering dianggap terlalu besar untuk zaman itu. Minke mendengarkan dengan takjub, menyadari bahwa ada dunia pemikiran yang jauh lebih luas daripada yang pernah diajarkan di bangku sekolahnya.

Ketika hari mulai gelap, ia pulang dengan pikiran yang dipenuhi pertanyaan-pertanyaan baru, pertanyaan yang tak lagi bisa ia abaikan begitu saja.`,

`Bab 3 — Keputusan

Minke menyadari bahwa jalan yang ia pilih tidak akan mudah, namun ia bertekad untuk terus menulis dan menyuarakan apa yang ia yakini benar, meski itu berarti berhadapan dengan pandangan orang-orang di sekelilingnya.

Guru-gurunya di sekolah mulai memperhatikan tulisannya, sebagian mendukung dengan diam-diam, sebagian lain merasa terganggu dengan pemikirannya yang dianggap terlalu berani untuk seorang pribumi muda.

Malam harinya, ia duduk sendirian di kamarnya, menimbang setiap konsekuensi dari pilihan yang telah ia ambil, namun keyakinannya justru semakin kuat setiap kali ia membaca kembali tulisannya sendiri.`,

`Bab 4 — Tekanan

Semakin banyak tulisannya dimuat, semakin besar pula perhatian dari pihak-pihak yang tidak menyukai gagasannya. Ia belajar bahwa setiap pemikiran punya risikonya sendiri, terutama ketika pemikiran itu menantang tatanan yang telah lama dianggap wajar.

Di tengah tekanan itu, ia justru menemukan keyakinan yang lebih kuat bahwa suara kaum pribumi harus terus didengar, apa pun konsekuensinya. Ia mulai memahami bahwa keberanian sejati bukan berarti tanpa rasa takut, melainkan tetap melangkah meski rasa takut itu ada.

Seorang sahabat memperingatkannya untuk berhati-hati, namun Minke hanya tersenyum dan berkata bahwa pena yang berhenti menulis sama saja dengan menyerah pada ketidakadilan.`,

`Bab 5 — Jalan Panjang

Minke menyadari bahwa perjuangannya baru saja dimulai. Ia mulai merancang tulisan-tulisan baru yang lebih tajam dan lebih berani dari sebelumnya, mempersiapkan diri untuk konsekuensi yang mungkin harus ia tanggung.

Ia mengingat kembali nasihat yang pernah diberikan kepadanya: bahwa ilmu pengetahuan tanpa keberanian untuk bertindak hanyalah pengetahuan yang mati, tak berguna bagi siapa pun yang membutuhkannya.

Di bawah cahaya lampu minyak, ia menutup buku catatannya malam itu dengan satu keyakinan: bahwa pena bisa menjadi senjata yang paling tajam sekalipun, mampu menembus dinding-dinding yang dibangun oleh kekuasaan yang tidak adil.`,

`Bab 6 — Warisan Pemikiran

Bertahun-tahun setelah peristiwa itu, tulisan-tulisan Minke ditemukan kembali oleh generasi muda yang haus akan sejarah bangsanya sendiri. Mereka membaca dengan takjub, menyadari betapa relevannya pertanyaan-pertanyaan yang diajukan puluhan tahun sebelumnya.

Seorang mahasiswa yang menemukan salinan tulisan itu di perpustakaan kampus merasa seolah sedang berbicara langsung dengan penulisnya, seakan jarak waktu yang begitu panjang tidak lagi berarti apa-apa di hadapan kata-kata yang jujur.

Ia menutup buku itu dengan perasaan campur aduk antara haru dan semangat baru, membawa pulang satu pelajaran penting: bahwa keberanian untuk berpikir berbeda selalu punya harganya, namun juga selalu punya artinya.`
    ],
    filosofi:[
`Bab 1 — Mengapa Kita Cemas

Kecemasan sering muncul bukan karena kejadian itu sendiri, melainkan karena cara kita memandang dan menilainya. Dua orang bisa mengalami situasi yang persis sama, namun bereaksi dengan cara yang sangat berbeda tergantung pada bagaimana pikiran mereka menafsirkan kejadian tersebut.

Para filsuf Stoa mengajarkan bahwa hal-hal di luar kendali kita — pendapat orang lain, cuaca, hasil akhir dari suatu usaha — sebaiknya tidak menjadi sumber utama kegelisahan kita sehari-hari.

Bayangkan seseorang yang terjebak macet menjelang rapat penting. Kemacetan itu di luar kendalinya, namun caranya bereaksi terhadap kemacetan itu sepenuhnya berada dalam kendalinya sendiri.`,

`Bab 2 — Dikotomi Kendali

Ada hal yang bisa kita kendalikan sepenuhnya: pikiran, penilaian, dan tindakan kita. Ada pula hal yang sama sekali di luar kendali kita, seperti pendapat orang lain tentang diri kita atau kejadian-kejadian di masa lalu yang tak bisa diubah lagi.

Dengan memahami batas ini, kita dapat mengarahkan energi hanya pada hal-hal yang benar-benar bisa kita ubah, alih-alih menghabiskan waktu untuk mengkhawatirkan sesuatu yang sama sekali tak bisa kita pengaruhi.

Latihan sederhana yang bisa dicoba adalah menuliskan sebuah masalah, lalu memisahkannya menjadi dua kolom: apa yang bisa saya kendalikan, dan apa yang tidak. Sering kali, daftar yang benar-benar bisa dikendalikan jauh lebih pendek dari yang kita kira.`,

`Bab 3 — Latihan Harian

Menuliskan jurnal refleksi setiap malam membantu melatih cara pandang yang lebih tenang terhadap masalah sehari-hari. Pertanyaan sederhana seperti "apa yang membuatku gelisah hari ini, dan apakah hal itu benar-benar berada dalam kendaliku" bisa menjadi titik awal yang baik.

Kebiasaan kecil ini, jika dilakukan konsisten, perlahan mengubah cara seseorang bereaksi terhadap tekanan dan kekecewaan. Alih-alih bereaksi secara impulsif, seseorang belajar untuk berhenti sejenak sebelum merespons.

Banyak orang yang mulai mempraktikkan kebiasaan ini melaporkan bahwa mereka merasa lebih tenang menghadapi kritik, lebih sabar menghadapi kegagalan, dan lebih fokus pada hal-hal yang benar-benar penting bagi mereka.`,

`Bab 4 — Amor Fati

Menerima apa yang terjadi, bahkan mencintainya sebagai bagian dari perjalanan hidup, adalah salah satu inti ajaran Stoisisme yang paling membebaskan. Konsep ini dikenal dengan istilah amor fati, atau cinta akan takdir.

Bukan berarti pasrah tanpa usaha, melainkan berhenti melawan hal-hal yang memang sudah tidak bisa diubah lagi. Seseorang yang kehilangan pekerjaan misalnya, tetap bisa berusaha mencari peluang baru tanpa harus terus-menerus meratapi apa yang telah hilang.

Prinsip ini mengajarkan bahwa setiap kesulitan menyimpan pelajaran tersembunyi, dan tugas kita bukanlah menghindarinya, melainkan mencari makna di baliknya.`,

`Bab 5 — Ketenangan sebagai Pilihan

Ketenangan bukan sesuatu yang datang begitu saja, melainkan hasil dari latihan berpikir yang dilakukan berulang-ulang setiap hari. Sama seperti otot yang menjadi kuat melalui latihan, ketenangan pikiran juga terbentuk melalui kebiasaan yang konsisten.

Dengan memahami prinsip ini, seseorang dapat menghadapi kecemasan sehari-hari dengan kepala yang lebih dingin dan hati yang lebih lapang, tanpa harus menekan atau mengabaikan perasaan yang muncul.

Pada akhirnya, filosofi ini bukan tentang menjadi kebal terhadap emosi, melainkan tentang belajar merespons emosi tersebut dengan cara yang lebih bijaksana dan tidak merugikan diri sendiri.`
    ],
    sapiens:[
`Bab 1 — Revolusi Kognitif

Sekitar tujuh puluh ribu tahun lalu, kemampuan berbahasa dan berimajinasi memungkinkan manusia bekerja sama dalam kelompok yang jauh lebih besar dibandingkan spesies lain di planet ini.

Kemampuan menciptakan cerita bersama — mitos, agama, bangsa, bahkan uang — menjadi fondasi dari seluruh peradaban yang kita kenal saat ini. Tidak seperti hewan lain yang hanya bisa bekerja sama dalam kelompok kecil berdasarkan ikatan langsung, manusia mampu percaya pada hal-hal abstrak yang menyatukan ribuan bahkan jutaan orang asing sekaligus.

Kepercayaan bersama inilah yang memungkinkan ribuan orang asing bekerja sama membangun piramida, kerajaan, hingga perusahaan multinasional, semuanya berdiri di atas cerita yang mereka sepakati bersama.`,

`Bab 2 — Revolusi Pertanian

Beralih dari berburu-meramu ke bercocok tanam mengubah cara hidup manusia secara mendasar, meski tidak selalu membawa kehidupan yang lebih mudah seperti yang sering dibayangkan orang.

Kepemilikan lahan dan surplus pangan melahirkan struktur sosial baru, termasuk hierarki dan ketimpangan yang belum pernah ada sebelumnya pada masa manusia masih hidup berpindah-pindah sebagai pemburu.

Ironisnya, banyak petani awal justru bekerja lebih keras dan memiliki pola makan yang kurang beragam dibandingkan nenek moyang mereka yang berburu dan meramu, meski populasi manusia secara keseluruhan tumbuh jauh lebih pesat.`,

`Bab 3 — Menuju Era Modern

Revolusi ilmiah dan teknologi mempercepat perubahan yang sebelumnya membutuhkan ribuan tahun menjadi hanya hitungan dekade. Penemuan mesin uap, listrik, hingga komputer masing-masing mengubah cara manusia bekerja dan berinteraksi secara radikal.

Penemuan-penemuan baru mengubah cara manusia memandang alam semesta, sekaligus membuka pertanyaan-pertanyaan besar tentang tempat manusia di dalamnya — apakah kita pusat dari segalanya, atau hanya salah satu spesies di antara miliaran lainnya.

Kecepatan perubahan ini juga membawa tantangan baru: masyarakat harus beradaptasi jauh lebih cepat dari yang pernah dialami generasi sebelumnya, sering kali tanpa waktu yang cukup untuk benar-benar memahami dampaknya.`,

`Bab 4 — Kapitalisme dan Globalisasi

Sistem ekonomi modern menyatukan hampir seluruh dunia ke dalam satu jaringan perdagangan dan kepercayaan bersama terhadap nilai uang, sebuah konsep yang sepenuhnya bergantung pada kepercayaan kolektif untuk bisa berfungsi.

Kepercayaan kolektif ini, meski tidak berwujud fisik, ternyata mampu menggerakkan hampir seluruh aktivitas manusia modern — dari perdagangan internasional hingga keputusan investasi jangka panjang.

Globalisasi juga menciptakan saling ketergantungan yang belum pernah terjadi sebelumnya: krisis di satu belahan dunia kini bisa dirasakan dampaknya hampir seketika di belahan dunia yang lain.`,

`Bab 5 — Masa Depan Spesies

Dengan kemajuan bioteknologi dan kecerdasan buatan, manusia kini berada di ambang perubahan besar berikutnya dalam sejarah evolusinya sendiri, sebuah babak yang mungkin akan mengubah definisi tentang apa artinya menjadi manusia.

Pertanyaan besarnya bukan lagi apa yang bisa kita ciptakan, melainkan ke arah mana sebaiknya kita mengarahkan kemampuan itu, mengingat teknologi yang sama bisa membawa kemajuan luar biasa sekaligus risiko yang belum pernah kita hadapi sebelumnya.

Buku ini mengajak pembacanya untuk merenungkan bukan hanya dari mana kita berasal, tetapi juga ke mana sebaiknya perjalanan panjang spesies ini akan menuju.`
    ],
    rich:[
`Bab 1 — Dua Cara Pandang

Ayah kaya mengajarkan bahwa uang seharusnya bekerja untuk kita, bukan sebaliknya kita bekerja seumur hidup hanya untuk uang. Prinsip sederhana ini menjadi fondasi dari seluruh cara pandang finansial yang dibagikan dalam buku ini.

Perbedaan cara berpikir tentang aset dan kewajiban menjadi titik awal dari seluruh pelajaran keuangan dalam buku ini, sebuah perbedaan yang tampak sederhana namun berdampak besar pada keputusan finansial jangka panjang.

Dua orang bisa memiliki penghasilan yang sama persis, namun berakhir dengan kondisi finansial yang jauh berbeda, semata karena cara mereka memandang dan mengelola uang yang mereka hasilkan.`,

`Bab 2 — Aset vs Kewajiban

Aset adalah sesuatu yang memasukkan uang ke kantong kita, sedangkan kewajiban adalah sesuatu yang justru mengeluarkan uang dari kantong kita, meski keduanya sering kali terlihat serupa dari luar.

Banyak orang keliru menganggap barang-barang mewah sebagai aset, padahal sebagian besar justru menjadi beban finansial jangka panjang karena biaya perawatan, penyusutan nilai, dan cicilan yang menyertainya.

Latihan sederhana yang bisa dilakukan adalah membuat daftar seluruh barang yang dimiliki, lalu menandai mana yang benar-benar menghasilkan uang dan mana yang justru terus-menerus menguras kantong setiap bulannya.`,

`Bab 3 — Membangun Literasi Finansial

Literasi keuangan dimulai dari kebiasaan kecil: mencatat pengeluaran, memahami arus kas, dan berinvestasi sejak dini, sekecil apa pun jumlahnya pada awalnya.

Semakin dini seseorang memahami cara kerja uang, semakin besar peluangnya untuk membangun kebebasan finansial di masa depan, karena waktu adalah salah satu aset paling berharga dalam dunia investasi.

Membaca laporan keuangan sederhana, memahami perbedaan antara utang produktif dan utang konsumtif, adalah keterampilan dasar yang sayangnya jarang diajarkan secara formal di bangku sekolah.`,

`Bab 4 — Bekerja untuk Belajar, Bukan untuk Uang

Di awal karier, pengalaman dan keterampilan baru sering kali lebih berharga daripada gaji besar semata, karena keterampilan itulah yang akan menentukan peluang-peluang di masa depan.

Kemampuan menjual, bernegosiasi, dan memahami sistem keuangan menjadi bekal penting yang jarang diajarkan secara formal di sekolah, namun sangat menentukan keberhasilan seseorang dalam membangun usaha maupun karier jangka panjang.

Banyak orang sukses justru memulai dari pekerjaan sederhana yang memberi mereka pelajaran berharga tentang bagaimana bisnis sesungguhnya berjalan, jauh sebelum mereka membangun usaha mereka sendiri.`,

`Bab 5 — Mengatasi Rasa Takut dan Kritik

Rasa takut gagal dan takut dikritik sering menjadi penghalang terbesar seseorang untuk mulai berinvestasi atau membuka usaha, bahkan ketika mereka sebenarnya memiliki pengetahuan yang cukup untuk memulai.

Dengan mengubah pola pikir terhadap risiko dan kegagalan, seseorang dapat mulai membangun jalan menuju kemandirian finansial secara bertahap, memperlakukan setiap kegagalan kecil sebagai pelajaran alih-alih alasan untuk berhenti.

Buku ini menutup dengan pesan sederhana namun kuat: kebebasan finansial bukan tentang seberapa banyak uang yang dihasilkan, melainkan seberapa baik seseorang memahami dan mengelola uang yang ia miliki.`
    ]
  };

  // ===================== PENYIMPANAN LOKAL (aman untuk Netlify / hosting statis) =====================
  // Menggunakan localStorage browser biasa, bukan window.storage (yang hanya tersedia di dalam Artifact Claude).
  function storageGet(key, fallback){
    try{
      const raw = localStorage.getItem(key);
      return raw ? JSON.parse(raw) : fallback;
    }catch(e){
      return fallback;
    }
  }
  function storageSet(key, value){
    try{
      localStorage.setItem(key, JSON.stringify(value));
      return true;
    }catch(e){
      console.error('Gagal menyimpan data', e);
      return false;
    }
  }

  // ===================== AKUN PENGGUNA =====================
  const DEFAULT_USERS = {
    'helena@kampus.ac.id': { name:'Maria Helena Waoma', nim:'1025720124', status:'Mahasiswa', pass:'12345678' }
  };
  const DEFAULT_ADMIN = {
    'pengelola.helena@perpustakaan.id': { name:'Admin Perpustakaan', pass:'H3l3na#Adm2026' }
  };

  let currentUserId = 'helena@kampus.ac.id';

  function getUsers(){ return storageGet('ph_users', DEFAULT_USERS); }
  function getAdmins(){ return storageGet('ph_admins', DEFAULT_ADMIN); }

  function doLogin(){
    const id = document.getElementById('login-id').value.trim().toLowerCase();
    const pass = document.getElementById('login-pass').value.trim();
    if(!id || !pass){ toast('Isi email dan kata sandi terlebih dahulu'); return; }

    // Deteksi otomatis: jika email yang dimasukkan cocok dengan akun administrator,
    // langsung arahkan ke Panel Administrator tanpa perlu layar atau gestur terpisah.
    const admins = getAdmins();
    const adminMatchKey = Object.keys(admins).find(k => k.toLowerCase() === id);
    if(adminMatchKey){
      const adminAcc = admins[adminMatchKey];
      if(adminAcc.pass !== pass){
        toast('Kata sandi administrator salah, silakan coba lagi');
        return;
      }
      document.getElementById('admin-greet-name').textContent = adminAcc.name + ' 🛠️';
      renderAdminBookList();
      go('admin-dashboard');
      toast('Masuk sebagai Administrator');
      return;
    }

    const users = getUsers();
    const matchKey = Object.keys(users).find(k => k.toLowerCase() === id);
    const acc = matchKey ? users[matchKey] : null;
    if(!acc){
      toast('Akun tidak ditemukan. Silakan daftar dulu.');
      go('register');
      return;
    }
    if(acc.pass !== pass){
      toast('Kata sandi salah, silakan coba lagi');
      return;
    }
    currentUserId = matchKey;
    const nameEl = document.querySelector('#screen-dashboard .greeting b');
    if(nameEl) nameEl.textContent = acc.name.split(' ')[0] + ' 👋';
    const avatarEl = document.querySelector('#screen-profil .avatar');
    if(avatarEl) avatarEl.textContent = acc.name.split(' ').filter(Boolean).slice(0,2).map(w=>w[0].toUpperCase()).join('');
    const profNameEl = document.querySelector('#screen-profil .profile-head h2');
    if(profNameEl) profNameEl.textContent = acc.name;
    const profSubEl = document.querySelector('#screen-profil .profile-head p');
    if(profSubEl) profSubEl.textContent = (acc.nim ? 'NIM ' + acc.nim + ' · ' : '') + (acc.status || 'Pengguna');
    renderSearchBookList();
    go('dashboard');
    toast('Selamat datang kembali, ' + acc.name.split(' ')[0]);
  }

  function doRegister(){
    const errBox = document.getElementById('reg-error');
    errBox.classList.remove('show');
    const name = document.getElementById('reg-name').value.trim();
    const nim = document.getElementById('reg-nim').value.trim();
    const email = document.getElementById('reg-email').value.trim().toLowerCase();
    const status = document.getElementById('reg-status').value;
    const pass = document.getElementById('reg-pass').value;

    if(!name || !email || !pass){
      errBox.textContent = 'Nama, email, dan kata sandi wajib diisi.';
      errBox.classList.add('show');
      return;
    }
    if(pass.length < 6){
      errBox.textContent = 'Kata sandi minimal 6 karakter.';
      errBox.classList.add('show');
      return;
    }
    const users = getUsers();
    if(users[email]){
      errBox.textContent = 'Email ini sudah terdaftar. Silakan masuk.';
      errBox.classList.add('show');
      return;
    }
    users[email] = { name, nim, status, pass };
    storageSet('ph_users', users);

    // Langsung masuk otomatis setelah daftar
    document.getElementById('login-id').value = email;
    document.getElementById('login-pass').value = pass;
    toast('Akun berhasil dibuat, langsung masuk');
    doLogin();
  }

  // ===================== LOGOUT =====================
  // Kosongkan kembali kolom email & kata sandi setiap kali logout (baik dari akun pengguna
  // maupun akun administrator), sehingga layar login selalu bersih saat dibuka kembali.
  function doLogout(){
    const loginId = document.getElementById('login-id');
    const loginPass = document.getElementById('login-pass');
    if(loginId) loginId.value = '';
    if(loginPass) loginPass.value = '';
    go('login');
  }

  // ===================== DATA BUKU (privat per instalasi, admin-managed) =====================
  const DEFAULT_BOOKS = {
    laut:{title:'Laut Bercerita', author:'Leila S. Chudori', tag1:'Fiksi Sejarah', stock:3, code:'LB', callno:'813.086 CHU',
          bg:'linear-gradient(160deg,#1B5A73,#123a4a)',
          desc:'Novel yang mengisahkan perjuangan aktivis mahasiswa pada masa kelam sejarah Indonesia, dituturkan dengan sudut pandang yang menyentuh dan penuh empati.'},
    bumi:{title:'Bumi Manusia', author:'Pramoedya A.T.', tag1:'Sastra Klasik', stock:2, code:'BM', callno:'899.221 TOE',
          bg:'linear-gradient(160deg,#C9973E,#8c6420)',
          desc:'Kisah Minke, pemuda pribumi di era kolonial, dalam pergulatan identitas, cinta, dan perlawanan terhadap ketidakadilan zaman.'},
    filosofi:{title:'Filosofi Teras', author:'Henry Manampiring', tag1:'Non-Fiksi', stock:1, code:'FT', callno:'188 MAN',
          bg:'linear-gradient(160deg,#6B7D82,#3c4c50)',
          desc:'Pengantar filsafat Stoisisme yang dikemas ringan dan aplikatif untuk menghadapi kecemasan hidup sehari-hari.'},
    sapiens:{title:'Sapiens', author:'Yuval Noah Harari', tag1:'Sains Populer', stock:4, code:'SP', callno:'909 HAR',
          bg:'linear-gradient(160deg,#8a5a3b,#4a2f1c)',
          desc:'Menelusuri perjalanan panjang spesies manusia, dari revolusi kognitif hingga revolusi teknologi yang membentuk dunia modern.'},
    rich:{title:'Rich Dad Poor Dad', author:'Robert T. Kiyosaki', tag1:'Ekonomi', stock:1, code:'RD', callno:'332.024 KIY',
          bg:'linear-gradient(160deg,#2f7d43,#173d21)',
          desc:'Membandingkan pola pikir finansial dua sosok ayah untuk mengajarkan prinsip dasar literasi keuangan dan kebebasan finansial.'}
  };

  let books = JSON.parse(JSON.stringify(DEFAULT_BOOKS));
  const bookGradients = [
    'linear-gradient(160deg,#1B5A73,#123a4a)','linear-gradient(160deg,#C9973E,#8c6420)',
    'linear-gradient(160deg,#6B7D82,#3c4c50)','linear-gradient(160deg,#8a5a3b,#4a2f1c)',
    'linear-gradient(160deg,#2f7d43,#173d21)','linear-gradient(160deg,#B5473B,#6e2c24)'
  ];

  function loadBooksFromStorage(){
    const saved = storageGet('ph_katalog_buku', null);
    books = saved ? saved : JSON.parse(JSON.stringify(DEFAULT_BOOKS));
    renderAdminBookList();
    renderSearchBookList();
  }

  function persistBooks(){
    storageSet('ph_katalog_buku', books);
  }

  function slugify(str){
    return 'buku_' + str.toLowerCase().replace(/[^a-z0-9]+/g,'_').replace(/^_+|_+$/g,'') + '_' + Math.floor(Math.random()*10000);
  }

  function initials(title){
    return title.split(' ').filter(Boolean).slice(0,2).map(w=>w[0].toUpperCase()).join('') || 'BK';
  }

  function saveBook(){
    const title = document.getElementById('af-title').value.trim();
    const author = document.getElementById('af-author').value.trim();
    const tag1 = document.getElementById('af-tag').value;
    const callno = document.getElementById('af-callno').value.trim() || '000 XXX';
    const stock = parseInt(document.getElementById('af-stock').value) || 0;
    const desc = document.getElementById('af-desc').value.trim() || 'Belum ada sinopsis untuk buku ini.';
    const editKey = document.getElementById('af-editkey').value;

    if(!title || !author){
      toast('Judul dan penulis wajib diisi');
      return;
    }

    if(editKey && books[editKey]){
      books[editKey].title = title;
      books[editKey].author = author;
      books[editKey].tag1 = tag1;
      books[editKey].callno = callno;
      books[editKey].stock = stock;
      books[editKey].desc = desc;
      toast('Buku berhasil diperbarui');
    } else {
      const key = slugify(title);
      books[key] = {
        title, author, tag1, callno, stock, desc,
        code: initials(title),
        bg: bookGradients[Object.keys(books).length % bookGradients.length]
      };
      toast('Buku baru berhasil ditambahkan ke katalog');
    }

    persistBooks();
    clearBookForm();
    renderAdminBookList();
    renderSearchBookList();
    go('admin-buku');
  }

  function clearBookForm(){
    document.getElementById('af-title').value='';
    document.getElementById('af-author').value='';
    document.getElementById('af-callno').value='';
    document.getElementById('af-stock').value=1;
    document.getElementById('af-desc').value='';
    document.getElementById('af-editkey').value='';
    document.getElementById('admin-form-title').textContent = 'Tambah Buku Baru';
  }

  function editBook(key){
    const b = books[key];
    document.getElementById('af-title').value = b.title;
    document.getElementById('af-author').value = b.author;
    document.getElementById('af-tag').value = b.tag1;
    document.getElementById('af-callno').value = b.callno;
    document.getElementById('af-stock').value = b.stock;
    document.getElementById('af-desc').value = b.desc;
    document.getElementById('af-editkey').value = key;
    document.getElementById('admin-form-title').textContent = 'Ubah Data Buku';
    go('admin-tambah');
  }

  function deleteBook(key){
    if(!books[key]) return;
    delete books[key];
    persistBooks();
    renderAdminBookList();
    renderSearchBookList();
    toast('Buku dihapus dari katalog');
  }

  function stockBadge(stock){
    if(stock <= 0) return '<span class="badge low">Stok habis</span>';
    if(stock <= 1) return `<span class="badge low">Sisa ${stock} eksemplar</span>`;
    return `<span class="badge ok">Tersedia · ${stock} eksemplar</span>`;
  }

  function renderAdminBookList(){
    const list = document.getElementById('admin-book-list');
    const recent = document.getElementById('admin-recent-books');
    if(!list) return;
    const entries = Object.entries(books);
    document.getElementById('admin-total-buku').textContent = entries.length;

    list.innerHTML = entries.map(([key,b])=>`
      <div class="admin-book-card">
        <div class="cover-art" style="width:44px;height:60px;border-radius:3px 6px 6px 3px;font-size:11px;padding-top:6px;background:${b.bg};">${b.code}</div>
        <div class="meta">
          <div class="title">${b.title}</div>
          <div class="sub">${b.author} · ${b.tag1}</div>
          ${stockBadge(b.stock)}
        </div>
        <div class="acts">
          <button class="icon-btn edit" onclick="editBook('${key}')">✏️</button>
          <button class="icon-btn del" onclick="deleteBook('${key}')">🗑️</button>
        </div>
      </div>
    `).join('') || '<div class="notif-card"><div class="ic">📭</div><div><div class="t">Katalog masih kosong</div><div class="d">Tambahkan judul buku pertama Anda.</div></div></div>';

    if(recent){
      recent.innerHTML = entries.slice(-3).reverse().map(([key,b])=>`
        <div class="admin-book-card" onclick="editBook('${key}')" style="cursor:pointer;">
          <div class="cover-art" style="width:44px;height:60px;border-radius:3px 6px 6px 3px;font-size:11px;padding-top:6px;background:${b.bg};">${b.code}</div>
          <div class="meta"><div class="title">${b.title}</div><div class="sub">${b.author}</div></div>
        </div>
      `).join('');
    }
  }

  function renderSearchBookList(){
    const container = document.getElementById('screen-cari').querySelector('.content');
    if(!container) return;
    let rowsHtml = document.getElementById('search-book-rows');
    if(!rowsHtml){
      rowsHtml = document.createElement('div');
      rowsHtml.id = 'search-book-rows';
      container.appendChild(rowsHtml);
    }
    rowsHtml.innerHTML = Object.entries(books).map(([key,b])=>`
      <div class="book-row" onclick="openBook('${key}')">
        <div class="cover-art" style="background:${b.bg};">${b.code}</div>
        <div class="meta">
          <div class="title">${b.title}</div>
          <div class="author">${b.author} · ${b.tag1}</div>
          ${stockBadge(b.stock)}
        </div>
      </div>
    `).join('');
  }

  let currentBookKey = 'laut';
  let currentPage = 0;
  let fontLevel = 1; // 0 kecil, 1 sedang, 2 besar
  const fontLabels = ['Kecil','Sedang','Besar'];
  const fontSizes = [12.5, 13.5, 16];

  function openEbook(){
    currentPage = 0;
    document.getElementById('ebook-header-title').textContent = books[currentBookKey].title;
    renderEbookPage();
    go('ebook');
  }

  function renderEbookPage(){
    const pages = ebookContent[currentBookKey];
    const raw = pages[currentPage].trim();
    const paras = raw.split(/\n\n+/).map(p => `<p>${p.replace(/\n/g,'<br>')}</p>`).join('');
    document.getElementById('reader-page-text').innerHTML = paras;
    document.getElementById('reader-page-count').textContent = 'Hal. ' + (currentPage+1) + ' / ' + pages.length;
  }

  function turnPage(dir){
    const pages = ebookContent[currentBookKey];
    const next = currentPage + dir;
    if(next < 0){ toast('Sudah di halaman pertama'); return; }
    if(next >= pages.length){ toast('Sudah mencapai halaman terakhir bab ini'); return; }
    currentPage = next;
    renderEbookPage();
  }

  function changeFontSize(){
    fontLevel = (fontLevel + 1) % 3;
    document.getElementById('font-size-label').textContent = fontLabels[fontLevel];
    document.getElementById('reader-page-text').style.fontSize = fontSizes[fontLevel] + 'px';
  }

  function toggleFavoriteReader(){
    const el = document.getElementById('reader-fav');
    if(el.textContent.includes('☆')){
      el.innerHTML = '★ Favorit';
      toast('Ditambahkan ke Rak Favorit');
    } else {
      el.innerHTML = '☆ Favorit';
      toast('Dihapus dari Rak Favorit');
    }
  }

  function go(id){
    document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
    document.getElementById('screen-'+id).classList.add('active');
    document.getElementById('phone').scrollTop = 0;
    if(id === 'admin-buku' || id === 'admin-dashboard') renderAdminBookList();
    if(id === 'cari') renderSearchBookList();
    if(id === 'admin-tambah' && !document.getElementById('af-editkey').value) clearBookForm();
  }

  function openBook(key){
    if(!books[key]){ toast('Buku tidak ditemukan'); return; }
    currentBookKey = key;
    const b = books[key];
    document.getElementById('detail-cover').style.background = b.bg;
    document.getElementById('detail-code').textContent = b.code;
    document.getElementById('detail-callno').textContent = b.callno;
    document.getElementById('detail-title').textContent = b.title;
    document.getElementById('detail-author').textContent = b.author;
    document.getElementById('detail-stock').textContent = (typeof b.stock === 'number' ? b.stock + ' eksemplar' : b.stock);
    document.getElementById('detail-desc').textContent = b.desc;
    document.getElementById('detail-tags').innerHTML = `<span class="tag">${b.tag1}</span><span class="tag">Indonesia</span>`;
    go('detail');
  }

  let toastTimer;
  function toast(msg){
    const t = document.getElementById('toast');
    t.textContent = msg;
    t.classList.add('show');
    clearTimeout(toastTimer);
    toastTimer = setTimeout(()=> t.classList.remove('show'), 1800);
  }

  // Muat katalog buku (privat/terkelola admin) begitu prototype dibuka
  window.addEventListener('DOMContentLoaded', ()=>{
    loadBooksFromStorage();

    // Pastikan kolom Email dan Kata Sandi di layar login benar-benar kosong
    // saat aplikasi pertama kali dibuka (mengatasi auto-fill browser).
    const loginId = document.getElementById('login-id');
    const loginPass = document.getElementById('login-pass');
    if(loginId) loginId.value = '';
    if(loginPass) loginPass.value = '';
  });

  // Sebagian browser mengisi ulang form (auto-fill) setelah event load selesai,
  // jadi kosongkan sekali lagi setelah halaman sepenuhnya termuat.
  window.addEventListener('load', ()=>{
    setTimeout(()=>{
      const loginId = document.getElementById('login-id');
      const loginPass = document.getElementById('login-pass');
      if(loginId) loginId.value = '';
      if(loginPass) loginPass.value = '';
    }, 50);
  });

  // Saat halaman dipulihkan dari cache back-forward (misalnya tombol kembali browser),
  // kosongkan lagi agar tidak menampilkan sisa input sebelumnya.
  window.addEventListener('pageshow', (event)=>{
    if(event.persisted){
      const loginId = document.getElementById('login-id');
      const loginPass = document.getElementById('login-pass');
      if(loginId) loginId.value = '';
      if(loginPass) loginPass.value = '';
    }
  });
</script>
</body>
</html>