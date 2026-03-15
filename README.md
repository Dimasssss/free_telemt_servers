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

# Server Metrics 2026-03-15 11:39:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 48291.7 (13h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207573
telemt_connections_bad_total 1391
telemt_handshake_timeouts_total 4545
telemt_upstream_connect_attempt_total 12299
telemt_upstream_connect_success_total 12234
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 12299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6798
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13186
telemt_me_reconnect_success_total 9817
telemt_me_reader_eof_total 10490
telemt_me_idle_close_by_peer_total 10490
telemt_me_route_drop_no_conn_total 420192
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254438
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1476
telemt_desync_full_logged_total 587
telemt_desync_suppressed_total 889
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 585
telemt_desync_frames_bucket_total{bucket="gt_10"} 648
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 10018
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 9786
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 193695
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 3658391036 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 188789577752 (175.82 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 48298.0 (13h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69636
telemt_connections_bad_total 2336
telemt_handshake_timeouts_total 3721
telemt_upstream_connect_attempt_total 13149
telemt_upstream_connect_success_total 13148
telemt_upstream_connect_attempts_per_request{bucket="1"} 13148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 13038
telemt_me_reconnect_success_total 10705
telemt_me_reader_eof_total 11464
telemt_me_idle_close_by_peer_total 11464
telemt_me_route_drop_no_conn_total 32640
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61287
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10894
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 10689
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 61286
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 1120824508 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 25358662164 (23.62 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 48290.8 (13h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76404
telemt_connections_bad_total 1012
telemt_handshake_timeouts_total 2555
telemt_upstream_connect_attempt_total 13792
telemt_upstream_connect_success_total 13784
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 13792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 13483
telemt_me_reconnect_success_total 11347
telemt_me_reader_eof_total 12156
telemt_me_idle_close_by_peer_total 12156
telemt_me_route_drop_no_conn_total 29198
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69531
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 11519
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 11339
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 69448
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 9479763704 (8.83 GB)
telemt_user_octets_to_client{user="hello"} 42969879932 (40.02 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 48290.3 (13h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102396
telemt_connections_bad_total 363
telemt_handshake_timeouts_total 676
telemt_upstream_connect_attempt_total 11409
telemt_upstream_connect_success_total 11408
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9045
telemt_me_reconnect_success_total 9000
telemt_me_reader_eof_total 9604
telemt_me_idle_close_by_peer_total 9604
telemt_me_route_drop_no_conn_total 41131
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93414
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 231
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9097
telemt_me_writer_restored_same_endpoint_total 8989
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 93335
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 1707584040 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 53529425820 (49.85 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 23361.8 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52542
telemt_connections_bad_total 13916
telemt_handshake_timeouts_total 848
telemt_upstream_connect_attempt_total 7756
telemt_upstream_connect_success_total 7699
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 7756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 100776
telemt_me_reconnect_success_total 6361
telemt_me_reader_eof_total 6608
telemt_me_idle_close_by_peer_total 6608
telemt_me_route_drop_no_conn_total 18491
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36569
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 70
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 6348
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6257
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 36706
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 552693333 (527.09 MB)
telemt_user_octets_to_client{user="hello"} 14389978047 (13.40 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 48289.5 (13h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271404
telemt_connections_bad_total 47258
telemt_handshake_timeouts_total 2020
telemt_upstream_connect_attempt_total 10240
telemt_upstream_connect_success_total 10178
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 10240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 7806
telemt_me_reconnect_success_total 7756
telemt_me_reader_eof_total 8265
telemt_me_idle_close_by_peer_total 8265
telemt_me_route_drop_no_conn_total 120062
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214235
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 90
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7820
telemt_me_writer_restored_same_endpoint_total 7729
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 212601
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 4775335504 (4.45 GB)
telemt_user_octets_to_client{user="hello"} 101182805068 (94.23 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 80
```