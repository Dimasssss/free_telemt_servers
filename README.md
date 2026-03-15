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

# Server Metrics 2026-03-15 19:59:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 78307.9 (21h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367574
telemt_connections_bad_total 4467
telemt_handshake_timeouts_total 13610
telemt_upstream_connect_attempt_total 18742
telemt_upstream_connect_success_total 18649
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 18742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 18165
telemt_me_reconnect_success_total 14764
telemt_me_reader_eof_total 15738
telemt_me_idle_close_by_peer_total 15738
telemt_me_route_drop_no_conn_total 475860
telemt_me_route_drop_channel_closed_total 77
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396585
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1945
telemt_desync_full_logged_total 765
telemt_desync_suppressed_total 1180
telemt_desync_frames_bucket_total{bucket="1_2"} 368
telemt_desync_frames_bucket_total{bucket="3_10"} 757
telemt_desync_frames_bucket_total{bucket="gt_10"} 820
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15033
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 14730
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 335648
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 7562812400 (7.04 GB)
telemt_user_octets_to_client{user="hello"} 258589285512 (240.83 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 78314.3 (21h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150804
telemt_connections_bad_total 2857
telemt_handshake_timeouts_total 13066
telemt_upstream_connect_attempt_total 21373
telemt_upstream_connect_success_total 21330
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 21373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 520
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1020
telemt_me_reconnect_attempts_total 19514
telemt_me_reconnect_success_total 17071
telemt_me_reader_eof_total 18205
telemt_me_idle_close_by_peer_total 18204
telemt_me_route_drop_no_conn_total 63048
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128629
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 17401
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 17055
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 128901
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 2385267061 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 63534877680 (59.17 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 78306.9 (21h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151720
telemt_connections_bad_total 1724
telemt_handshake_timeouts_total 3374
telemt_upstream_connect_attempt_total 22502
telemt_upstream_connect_success_total 22494
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 22502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 25917
telemt_me_reconnect_success_total 18552
telemt_me_reader_eof_total 19918
telemt_me_idle_close_by_peer_total 19918
telemt_me_route_drop_no_conn_total 59712
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134347
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 18967
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 18544
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 415
telemt_user_connections_total{user="hello"} 134234
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 10856167856 (10.11 GB)
telemt_user_octets_to_client{user="hello"} 74328124548 (69.22 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 78306.5 (21h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217230
telemt_connections_bad_total 1171
telemt_handshake_timeouts_total 1573
telemt_upstream_connect_attempt_total 18323
telemt_upstream_connect_success_total 18308
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 18323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 14514
telemt_me_reconnect_success_total 14426
telemt_me_reader_eof_total 15363
telemt_me_idle_close_by_peer_total 15363
telemt_me_route_drop_no_conn_total 80201
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200082
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 712
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 242
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 14598
telemt_me_writer_restored_same_endpoint_total 14415
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 200000
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 3736617288 (3.48 GB)
telemt_user_octets_to_client{user="hello"} 91138012884 (84.88 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 53377.9 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130088
telemt_connections_bad_total 25690
telemt_handshake_timeouts_total 2504
telemt_upstream_connect_attempt_total 15690
telemt_upstream_connect_success_total 15593
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 15690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 107186
telemt_me_reconnect_success_total 12736
telemt_me_reader_eof_total 13400
telemt_me_idle_close_by_peer_total 13400
telemt_me_route_drop_no_conn_total 44310
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98309
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 309
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 12821
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 12632
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 98439
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 1589112885 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 38321480135 (35.69 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 78306.0 (21h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 531166
telemt_connections_bad_total 58018
telemt_handshake_timeouts_total 4282
telemt_upstream_connect_attempt_total 16650
telemt_upstream_connect_success_total 16555
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 16650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13953
telemt_me_reconnect_success_total 12643
telemt_me_reader_eof_total 13433
telemt_me_idle_close_by_peer_total 13433
telemt_me_route_drop_no_conn_total 374332
telemt_me_route_drop_channel_closed_total 91
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 512787
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 322
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 12819
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 12616
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 449116
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 11425974108 (10.64 GB)
telemt_user_octets_to_client{user="hello"} 256060987272 (238.48 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 61
```