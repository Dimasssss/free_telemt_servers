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

# Server Metrics 2026-03-12 11:11:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13070.9 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68587
telemt_connections_bad_total 494
telemt_handshake_timeouts_total 2613
telemt_upstream_connect_attempt_total 3212
telemt_upstream_connect_success_total 3199
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 2523
telemt_me_reconnect_success_total 2508
telemt_me_reader_eof_total 2610
telemt_me_idle_close_by_peer_total 2609
telemt_me_route_drop_no_conn_total 18809
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61982
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 259
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2522
telemt_me_writer_restored_same_endpoint_total 2492
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 61971
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 913529840 (871.21 MB)
telemt_user_octets_to_client{user="hello"} 20140841676 (18.76 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12963.1 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27640
telemt_connections_bad_total 221
telemt_handshake_timeouts_total 243
telemt_upstream_connect_attempt_total 4572
telemt_upstream_connect_success_total 4474
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 4572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 11419
telemt_me_reconnect_success_total 3790
telemt_me_reader_eof_total 4072
telemt_me_idle_close_by_peer_total 4072
telemt_me_route_drop_no_conn_total 11353
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26275
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 4042
telemt_me_refill_failed_total 238
telemt_me_writer_restored_same_endpoint_total 3775
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 26273
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 276578832 (263.77 MB)
telemt_user_octets_to_client{user="hello"} 5889012304 (5.48 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12927.1 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38943
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 328
telemt_upstream_connect_attempt_total 3592
telemt_upstream_connect_success_total 3592
telemt_upstream_connect_attempts_per_request{bucket="1"} 3592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 2913
telemt_me_reconnect_success_total 2895
telemt_me_reader_eof_total 3037
telemt_me_idle_close_by_peer_total 3037
telemt_me_route_drop_no_conn_total 12598
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36480
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2901
telemt_me_writer_restored_same_endpoint_total 2875
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 36467
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 483839580 (461.43 MB)
telemt_user_octets_to_client{user="hello"} 30012001880 (27.95 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 12902.3 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47204
telemt_connections_bad_total 1035
telemt_handshake_timeouts_total 249
telemt_upstream_connect_attempt_total 3848
telemt_upstream_connect_success_total 3760
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 3848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 166
telemt_me_reconnect_attempts_total 4257
telemt_me_reconnect_success_total 3064
telemt_me_reader_eof_total 3214
telemt_me_idle_close_by_peer_total 3214
telemt_me_route_drop_no_conn_total 14824
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42991
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 161
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3145
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 3056
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 42990
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 932656852 (889.45 MB)
telemt_user_octets_to_client{user="hello"} 26133001872 (24.34 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12871.7 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24868
telemt_connections_bad_total 2459
telemt_handshake_timeouts_total 391
telemt_upstream_connect_attempt_total 4071
telemt_upstream_connect_success_total 3910
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 4071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 14582
telemt_me_reconnect_success_total 3220
telemt_me_reader_eof_total 3571
telemt_me_idle_close_by_peer_total 3571
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 7383
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21316
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 332
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3594
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 3204
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 374
telemt_user_connections_total{user="hello"} 21313
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 130608292 (124.56 MB)
telemt_user_octets_to_client{user="hello"} 5623145212 (5.24 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 12858.7 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66830
telemt_connections_bad_total 585
telemt_handshake_timeouts_total 720
telemt_upstream_connect_attempt_total 2553
telemt_upstream_connect_success_total 2539
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 1872
telemt_me_reconnect_success_total 1858
telemt_me_reader_eof_total 1953
telemt_me_idle_close_by_peer_total 1953
telemt_me_route_drop_no_conn_total 28828
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63197
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 162
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1879
telemt_me_writer_restored_same_endpoint_total 1851
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 63161
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 1996902332 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 34345402360 (31.99 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 54
```