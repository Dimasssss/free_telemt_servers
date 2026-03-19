# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 11:35:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 49646.1 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1193211
telemt_connections_bad_total 100445
telemt_connections_current 1648
telemt_connections_me_current 1648
telemt_handshake_timeouts_total 41569
telemt_upstream_connect_attempt_total 9549
telemt_upstream_connect_success_total 9384
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 9549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 8756
telemt_me_reconnect_success_total 6870
telemt_me_reader_eof_total 7275
telemt_me_idle_close_by_peer_total 7272
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 500140
telemt_me_route_drop_channel_closed_total 192
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 932618
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5198
telemt_desync_full_logged_total 1583
telemt_desync_suppressed_total 3615
telemt_desync_frames_bucket_total{bucket="1_2"} 1700
telemt_desync_frames_bucket_total{bucket="3_10"} 1884
telemt_desync_frames_bucket_total{bucket="gt_10"} 1614
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 7028
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 6849
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 926557
telemt_user_connections_current{user="hello"} 1648
telemt_user_octets_from_client{user="hello"} 14249042112 (13.27 GB)
telemt_user_octets_to_client{user="hello"} 282298644988 (262.91 GB)
telemt_user_unique_ips_current{user="hello"} 569
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 49651.0 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3216176
telemt_connections_bad_total 208619
telemt_connections_current 4022
telemt_connections_me_current 4022
telemt_handshake_timeouts_total 60803
telemt_upstream_connect_attempt_total 9417
telemt_upstream_connect_success_total 9245
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 9417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4538
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 14696
telemt_me_reconnect_success_total 6703
telemt_me_reader_eof_total 7271
telemt_me_idle_close_by_peer_total 7270
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 2282757
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2699079
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10913
telemt_desync_full_logged_total 3651
telemt_desync_suppressed_total 7262
telemt_desync_frames_bucket_total{bucket="1_2"} 2118
telemt_desync_frames_bucket_total{bucket="3_10"} 4272
telemt_desync_frames_bucket_total{bucket="gt_10"} 4523
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7071
telemt_me_refill_failed_total 249
telemt_me_writer_restored_same_endpoint_total 6681
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 2698676
telemt_user_connections_current{user="hello"} 4022
telemt_user_octets_from_client{user="hello"} 36373702228 (33.88 GB)
telemt_user_octets_to_client{user="hello"} 829910051380 (772.91 GB)
telemt_user_unique_ips_current{user="hello"} 1351
telemt_user_unique_ips_recent_window{user="hello"} 1156
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 49648.4 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2517278
telemt_connections_bad_total 294539
telemt_connections_current 3260
telemt_connections_me_current 3260
telemt_handshake_timeouts_total 51833
telemt_upstream_connect_attempt_total 8939
telemt_upstream_connect_success_total 8939
telemt_upstream_connect_attempts_per_request{bucket="1"} 8939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 7593
telemt_me_reconnect_success_total 6399
telemt_me_reader_eof_total 6795
telemt_me_idle_close_by_peer_total 6794
telemt_me_route_drop_no_conn_total 1554225
telemt_me_route_drop_channel_closed_total 80
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1981903
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8230
telemt_desync_full_logged_total 2614
telemt_desync_suppressed_total 5616
telemt_desync_frames_bucket_total{bucket="1_2"} 1855
telemt_desync_frames_bucket_total{bucket="3_10"} 3027
telemt_desync_frames_bucket_total{bucket="gt_10"} 3348
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6546
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6383
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 1979695
telemt_user_connections_current{user="hello"} 3260
telemt_user_octets_from_client{user="hello"} 27676294972 (25.78 GB)
telemt_user_octets_to_client{user="hello"} 843505427904 (785.58 GB)
telemt_user_unique_ips_current{user="hello"} 1113
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 49701.8 (13h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2587277
telemt_connections_bad_total 135747
telemt_connections_current 3642
telemt_connections_me_current 3642
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 64327
telemt_upstream_connect_attempt_total 17255
telemt_upstream_connect_success_total 17080
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 17255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 10720
telemt_me_reconnect_success_total 6374
telemt_me_reader_eof_total 6794
telemt_me_idle_close_by_peer_total 6793
telemt_me_route_drop_no_conn_total 1685841
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1997765
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6987
telemt_desync_full_logged_total 2347
telemt_desync_suppressed_total 4640
telemt_desync_frames_bucket_total{bucket="1_2"} 1490
telemt_desync_frames_bucket_total{bucket="3_10"} 2746
telemt_desync_frames_bucket_total{bucket="gt_10"} 2751
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6843
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 6350
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 2003900
telemt_user_connections_current{user="hello"} 3642
telemt_user_octets_from_client{user="hello"} 22564551640 (21.01 GB)
telemt_user_octets_to_client{user="hello"} 538771029738 (501.77 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 971
telemt_user_unique_ips_recent_window{user="hello"} 540
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 49645.1 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2998956
telemt_connections_bad_total 653685
telemt_connections_current 3677
telemt_connections_me_current 3677
telemt_handshake_timeouts_total 59539
telemt_upstream_connect_attempt_total 8835
telemt_upstream_connect_success_total 8770
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 8835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 7452
telemt_me_reconnect_success_total 6247
telemt_me_reader_eof_total 6635
telemt_me_idle_close_by_peer_total 6634
telemt_me_route_drop_no_conn_total 1117572
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1984890
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8652
telemt_desync_full_logged_total 2683
telemt_desync_suppressed_total 5969
telemt_desync_frames_bucket_total{bucket="1_2"} 1630
telemt_desync_frames_bucket_total{bucket="3_10"} 3755
telemt_desync_frames_bucket_total{bucket="gt_10"} 3267
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6377
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6223
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 1983535
telemt_user_connections_current{user="hello"} 3677
telemt_user_octets_from_client{user="hello"} 34263875404 (31.91 GB)
telemt_user_octets_to_client{user="hello"} 800387649216 (745.42 GB)
telemt_user_unique_ips_current{user="hello"} 1251
telemt_user_unique_ips_recent_window{user="hello"} 587
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 49657.5 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519024
telemt_connections_bad_total 18614
telemt_connections_current 986
telemt_connections_me_current 986
telemt_handshake_timeouts_total 4048
telemt_upstream_connect_attempt_total 12330
telemt_upstream_connect_success_total 12013
telemt_upstream_connect_fail_total 317
telemt_upstream_connect_attempts_per_request{bucket="1"} 12330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6091
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 317
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 17073
telemt_me_reconnect_success_total 9485
telemt_me_reader_eof_total 10115
telemt_me_idle_close_by_peer_total 10115
telemt_me_route_drop_no_conn_total 270488
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 471038
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1012
telemt_desync_full_logged_total 355
telemt_desync_suppressed_total 657
telemt_desync_frames_bucket_total{bucket="1_2"} 213
telemt_desync_frames_bucket_total{bucket="3_10"} 408
telemt_desync_frames_bucket_total{bucket="gt_10"} 391
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9809
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9454
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 470978
telemt_user_connections_current{user="hello"} 986
telemt_user_octets_from_client{user="hello"} 7553877768 (7.04 GB)
telemt_user_octets_to_client{user="hello"} 173169853944 (161.28 GB)
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 49647.4 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2102990
telemt_connections_bad_total 175330
telemt_connections_current 3344
telemt_connections_me_current 3344
telemt_handshake_timeouts_total 72732
telemt_upstream_connect_attempt_total 9955
telemt_upstream_connect_success_total 9954
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 8779
telemt_me_reconnect_success_total 7411
telemt_me_reader_eof_total 7848
telemt_me_idle_close_by_peer_total 7847
telemt_me_route_drop_no_conn_total 1062167
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1755809
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9531
telemt_desync_full_logged_total 3073
telemt_desync_suppressed_total 6458
telemt_desync_frames_bucket_total{bucket="1_2"} 1811
telemt_desync_frames_bucket_total{bucket="3_10"} 3638
telemt_desync_frames_bucket_total{bucket="gt_10"} 4082
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7550
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7396
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 1754499
telemt_user_connections_current{user="hello"} 3344
telemt_user_octets_from_client{user="hello"} 23183847276 (21.59 GB)
telemt_user_octets_to_client{user="hello"} 779467827360 (725.94 GB)
telemt_user_unique_ips_current{user="hello"} 1029
telemt_user_unique_ips_recent_window{user="hello"} 468
```