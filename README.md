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

# Server Metrics 2026-03-19 09:17:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 41350.2 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 839824
telemt_connections_bad_total 79559
telemt_connections_current 1525
telemt_connections_me_current 1525
telemt_handshake_timeouts_total 33247
telemt_upstream_connect_attempt_total 7875
telemt_upstream_connect_success_total 7738
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 7875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6836
telemt_me_reconnect_success_total 5680
telemt_me_reader_eof_total 6012
telemt_me_idle_close_by_peer_total 6011
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 284767
telemt_me_route_drop_channel_closed_total 111
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 652120
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4065
telemt_desync_full_logged_total 1212
telemt_desync_suppressed_total 2853
telemt_desync_frames_bucket_total{bucket="1_2"} 1361
telemt_desync_frames_bucket_total{bucket="3_10"} 1486
telemt_desync_frames_bucket_total{bucket="gt_10"} 1218
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5782
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5661
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 647064
telemt_user_connections_current{user="hello"} 1525
telemt_user_octets_from_client{user="hello"} 10145355200 (9.45 GB)
telemt_user_octets_to_client{user="hello"} 211199330604 (196.69 GB)
telemt_user_unique_ips_current{user="hello"} 544
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 41355.0 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2061565
telemt_connections_bad_total 110297
telemt_connections_current 4395
telemt_connections_me_current 4395
telemt_handshake_timeouts_total 45865
telemt_upstream_connect_attempt_total 7869
telemt_upstream_connect_success_total 7723
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 7869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 7927
telemt_me_reconnect_success_total 5646
telemt_me_reader_eof_total 5999
telemt_me_idle_close_by_peer_total 5999
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 926598
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1717146
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7640
telemt_desync_full_logged_total 2584
telemt_desync_suppressed_total 5056
telemt_desync_frames_bucket_total{bucket="1_2"} 1384
telemt_desync_frames_bucket_total{bucket="3_10"} 2944
telemt_desync_frames_bucket_total{bucket="gt_10"} 3312
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5817
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 5624
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 1716912
telemt_user_connections_current{user="hello"} 4395
telemt_user_octets_from_client{user="hello"} 28262664052 (26.32 GB)
telemt_user_octets_to_client{user="hello"} 640673829388 (596.67 GB)
telemt_user_unique_ips_current{user="hello"} 1447
telemt_user_unique_ips_recent_window{user="hello"} 657
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 41352.2 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1760183
telemt_connections_bad_total 213591
telemt_connections_current 3174
telemt_connections_me_current 3174
telemt_handshake_timeouts_total 43177
telemt_upstream_connect_attempt_total 7373
telemt_upstream_connect_success_total 7373
telemt_upstream_connect_attempts_per_request{bucket="1"} 7373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3496
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5329
telemt_me_reconnect_success_total 5297
telemt_me_reader_eof_total 5602
telemt_me_idle_close_by_peer_total 5602
telemt_me_route_drop_no_conn_total 827558
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1366514
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6216
telemt_desync_full_logged_total 1943
telemt_desync_suppressed_total 4273
telemt_desync_frames_bucket_total{bucket="1_2"} 1412
telemt_desync_frames_bucket_total{bucket="3_10"} 2248
telemt_desync_frames_bucket_total{bucket="gt_10"} 2556
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5391
telemt_me_writer_restored_same_endpoint_total 5281
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 1365178
telemt_user_connections_current{user="hello"} 3174
telemt_user_octets_from_client{user="hello"} 21329889504 (19.87 GB)
telemt_user_octets_to_client{user="hello"} 638078645896 (594.26 GB)
telemt_user_unique_ips_current{user="hello"} 1079
telemt_user_unique_ips_recent_window{user="hello"} 505
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 41405.5 (11h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1833735
telemt_connections_bad_total 100297
telemt_connections_current 3091
telemt_connections_me_current 3091
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 46326
telemt_upstream_connect_attempt_total 15584
telemt_upstream_connect_success_total 15475
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 15584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4264
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7650
telemt_me_reconnect_success_total 5243
telemt_me_reader_eof_total 5570
telemt_me_idle_close_by_peer_total 5569
telemt_me_route_drop_no_conn_total 924296
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1357986
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4944
telemt_desync_full_logged_total 1682
telemt_desync_suppressed_total 3262
telemt_desync_frames_bucket_total{bucket="1_2"} 1013
telemt_desync_frames_bucket_total{bucket="3_10"} 1932
telemt_desync_frames_bucket_total{bucket="gt_10"} 1999
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5510
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5219
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 1364658
telemt_user_connections_current{user="hello"} 3091
telemt_user_octets_from_client{user="hello"} 16340572272 (15.22 GB)
telemt_user_octets_to_client{user="hello"} 399399596378 (371.97 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1010
telemt_user_unique_ips_recent_window{user="hello"} 489
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 41348.7 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2121036
telemt_connections_bad_total 519010
telemt_connections_current 3576
telemt_connections_me_current 3576
telemt_handshake_timeouts_total 44960
telemt_upstream_connect_attempt_total 7144
telemt_upstream_connect_success_total 7094
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 7144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 5070
telemt_me_reconnect_success_total 5027
telemt_me_reader_eof_total 5321
telemt_me_idle_close_by_peer_total 5321
telemt_me_route_drop_no_conn_total 605348
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1347135
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6354
telemt_desync_full_logged_total 1979
telemt_desync_suppressed_total 4375
telemt_desync_frames_bucket_total{bucket="1_2"} 1276
telemt_desync_frames_bucket_total{bucket="3_10"} 2801
telemt_desync_frames_bucket_total{bucket="gt_10"} 2277
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 5101
telemt_me_writer_restored_same_endpoint_total 5003
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1346358
telemt_user_connections_current{user="hello"} 3576
telemt_user_octets_from_client{user="hello"} 25739877524 (23.97 GB)
telemt_user_octets_to_client{user="hello"} 602657141020 (561.27 GB)
telemt_user_unique_ips_current{user="hello"} 1192
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 41361.1 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376338
telemt_connections_bad_total 17481
telemt_connections_current 960
telemt_connections_me_current 960
telemt_handshake_timeouts_total 3089
telemt_upstream_connect_attempt_total 10447
telemt_upstream_connect_success_total 10181
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 10447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 13496
telemt_me_reconnect_success_total 8113
telemt_me_reader_eof_total 8612
telemt_me_idle_close_by_peer_total 8612
telemt_me_route_drop_no_conn_total 192820
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336543
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 531
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 345
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 170
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 193
telemt_me_writer_removed_unexpected_total 8346
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8083
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 336510
telemt_user_connections_current{user="hello"} 960
telemt_user_octets_from_client{user="hello"} 4806169108 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 138372578980 (128.87 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 41351.2 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1432819
telemt_connections_bad_total 127554
telemt_connections_current 3109
telemt_connections_me_current 3109
telemt_handshake_timeouts_total 62633
telemt_upstream_connect_attempt_total 8381
telemt_upstream_connect_success_total 8380
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3892
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7653
telemt_me_reconnect_success_total 6306
telemt_me_reader_eof_total 6674
telemt_me_idle_close_by_peer_total 6673
telemt_me_route_drop_no_conn_total 567902
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1188532
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6778
telemt_desync_full_logged_total 2223
telemt_desync_suppressed_total 4555
telemt_desync_frames_bucket_total{bucket="1_2"} 1267
telemt_desync_frames_bucket_total{bucket="3_10"} 2560
telemt_desync_frames_bucket_total{bucket="gt_10"} 2951
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6422
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6291
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 1187425
telemt_user_connections_current{user="hello"} 3109
telemt_user_octets_from_client{user="hello"} 16420071560 (15.29 GB)
telemt_user_octets_to_client{user="hello"} 585371030864 (545.17 GB)
telemt_user_unique_ips_current{user="hello"} 1025
telemt_user_unique_ips_recent_window{user="hello"} 450
```