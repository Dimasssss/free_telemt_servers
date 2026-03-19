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

# Server Metrics 2026-03-19 11:05:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 47794.7 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1118590
telemt_connections_bad_total 95276
telemt_connections_current 1606
telemt_connections_me_current 1606
telemt_handshake_timeouts_total 39381
telemt_upstream_connect_attempt_total 9161
telemt_upstream_connect_success_total 8999
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 9161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4605
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 7748
telemt_me_reconnect_success_total 6583
telemt_me_reader_eof_total 6946
telemt_me_idle_close_by_peer_total 6943
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 453461
telemt_me_route_drop_channel_closed_total 171
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 869938
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4859
telemt_desync_full_logged_total 1490
telemt_desync_suppressed_total 3369
telemt_desync_frames_bucket_total{bucket="1_2"} 1592
telemt_desync_frames_bucket_total{bucket="3_10"} 1777
telemt_desync_frames_bucket_total{bucket="gt_10"} 1490
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6714
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 6562
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 863879
telemt_user_connections_current{user="hello"} 1606
telemt_user_octets_from_client{user="hello"} 12929140644 (12.04 GB)
telemt_user_octets_to_client{user="hello"} 265694940360 (247.45 GB)
telemt_user_unique_ips_current{user="hello"} 546
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 47798.6 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2962238
telemt_connections_bad_total 170653
telemt_connections_current 4221
telemt_connections_me_current 4221
telemt_handshake_timeouts_total 57099
telemt_upstream_connect_attempt_total 9098
telemt_upstream_connect_success_total 8932
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 9098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 11278
telemt_me_reconnect_success_total 6518
telemt_me_reader_eof_total 6983
telemt_me_idle_close_by_peer_total 6982
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 2023376
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2500560
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10150
telemt_desync_full_logged_total 3402
telemt_desync_suppressed_total 6748
telemt_desync_frames_bucket_total{bucket="1_2"} 1943
telemt_desync_frames_bucket_total{bucket="3_10"} 4017
telemt_desync_frames_bucket_total{bucket="gt_10"} 4190
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6783
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 6496
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 2500175
telemt_user_connections_current{user="hello"} 4221
telemt_user_octets_from_client{user="hello"} 34692438208 (32.31 GB)
telemt_user_octets_to_client{user="hello"} 789640579452 (735.41 GB)
telemt_user_unique_ips_current{user="hello"} 1380
telemt_user_unique_ips_recent_window{user="hello"} 727
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 47796.0 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2355009
telemt_connections_bad_total 271461
telemt_connections_current 3248
telemt_connections_me_current 3248
telemt_handshake_timeouts_total 50428
telemt_upstream_connect_attempt_total 8599
telemt_upstream_connect_success_total 8599
telemt_upstream_connect_attempts_per_request{bucket="1"} 8599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 6202
telemt_me_reconnect_success_total 6160
telemt_me_reader_eof_total 6505
telemt_me_idle_close_by_peer_total 6505
telemt_me_route_drop_no_conn_total 1466252
telemt_me_route_drop_channel_closed_total 75
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1856954
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7833
telemt_desync_full_logged_total 2494
telemt_desync_suppressed_total 5339
telemt_desync_frames_bucket_total{bucket="1_2"} 1743
telemt_desync_frames_bucket_total{bucket="3_10"} 2894
telemt_desync_frames_bucket_total{bucket="gt_10"} 3196
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6268
telemt_me_writer_restored_same_endpoint_total 6144
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 1855264
telemt_user_connections_current{user="hello"} 3248
telemt_user_octets_from_client{user="hello"} 26122356528 (24.33 GB)
telemt_user_octets_to_client{user="hello"} 790855954528 (736.54 GB)
telemt_user_unique_ips_current{user="hello"} 1118
telemt_user_unique_ips_recent_window{user="hello"} 642
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 47849.0 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2343128
telemt_connections_bad_total 126090
telemt_connections_current 3239
telemt_connections_me_current 3239
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 61111
telemt_upstream_connect_attempt_total 16932
telemt_upstream_connect_success_total 16765
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 16932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4868
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9814
telemt_me_reconnect_success_total 6150
telemt_me_reader_eof_total 6533
telemt_me_idle_close_by_peer_total 6532
telemt_me_route_drop_no_conn_total 1187529
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1774912
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6502
telemt_desync_full_logged_total 2195
telemt_desync_suppressed_total 4307
telemt_desync_frames_bucket_total{bucket="1_2"} 1373
telemt_desync_frames_bucket_total{bucket="3_10"} 2518
telemt_desync_frames_bucket_total{bucket="gt_10"} 2611
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6591
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 6126
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 1781093
telemt_user_connections_current{user="hello"} 3239
telemt_user_octets_from_client{user="hello"} 20187225516 (18.80 GB)
telemt_user_octets_to_client{user="hello"} 513109208270 (477.87 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1059
telemt_user_unique_ips_recent_window{user="hello"} 585
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 47792.4 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2801724
telemt_connections_bad_total 626417
telemt_connections_current 3553
telemt_connections_me_current 3553
telemt_handshake_timeouts_total 55017
telemt_upstream_connect_attempt_total 8480
telemt_upstream_connect_success_total 8420
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7206
telemt_me_reconnect_success_total 6005
telemt_me_reader_eof_total 6372
telemt_me_idle_close_by_peer_total 6371
telemt_me_route_drop_no_conn_total 1032302
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1846046
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8117
telemt_desync_full_logged_total 2527
telemt_desync_suppressed_total 5590
telemt_desync_frames_bucket_total{bucket="1_2"} 1572
telemt_desync_frames_bucket_total{bucket="3_10"} 3499
telemt_desync_frames_bucket_total{bucket="gt_10"} 3046
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6131
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5981
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 1845121
telemt_user_connections_current{user="hello"} 3553
telemt_user_octets_from_client{user="hello"} 32668857004 (30.43 GB)
telemt_user_octets_to_client{user="hello"} 753688835408 (701.93 GB)
telemt_user_unique_ips_current{user="hello"} 1203
telemt_user_unique_ips_recent_window{user="hello"} 627
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 47804.8 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485950
telemt_connections_bad_total 18504
telemt_connections_current 987
telemt_connections_me_current 987
telemt_handshake_timeouts_total 3801
telemt_upstream_connect_attempt_total 11985
telemt_upstream_connect_success_total 11678
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 11985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 15676
telemt_me_reconnect_success_total 9256
telemt_me_reader_eof_total 9831
telemt_me_idle_close_by_peer_total 9831
telemt_me_route_drop_no_conn_total 251999
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 439596
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 911
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 600
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 366
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9539
telemt_me_refill_failed_total 199
telemt_me_writer_restored_same_endpoint_total 9226
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 439546
telemt_user_connections_current{user="hello"} 987
telemt_user_octets_from_client{user="hello"} 7147231436 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 165320091536 (153.97 GB)
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 47794.7 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1967678
telemt_connections_bad_total 170083
telemt_connections_current 3249
telemt_connections_me_current 3249
telemt_handshake_timeouts_total 71559
telemt_upstream_connect_attempt_total 9605
telemt_upstream_connect_success_total 9604
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8534
telemt_me_reconnect_success_total 7168
telemt_me_reader_eof_total 7592
telemt_me_idle_close_by_peer_total 7591
telemt_me_route_drop_no_conn_total 975817
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1632410
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8896
telemt_desync_full_logged_total 2863
telemt_desync_suppressed_total 6033
telemt_desync_frames_bucket_total{bucket="1_2"} 1706
telemt_desync_frames_bucket_total{bucket="3_10"} 3384
telemt_desync_frames_bucket_total{bucket="gt_10"} 3806
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7302
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7153
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 1631128
telemt_user_connections_current{user="hello"} 3249
telemt_user_octets_from_client{user="hello"} 21837290452 (20.34 GB)
telemt_user_octets_to_client{user="hello"} 730706468716 (680.52 GB)
telemt_user_unique_ips_current{user="hello"} 1018
telemt_user_unique_ips_recent_window{user="hello"} 469
```