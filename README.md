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

# Server Metrics 2026-03-14 17:29:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 15190.3 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86911
telemt_connections_bad_total 13341
telemt_handshake_timeouts_total 469
telemt_upstream_connect_attempt_total 3630
telemt_upstream_connect_success_total 3628
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 2858
telemt_me_reconnect_success_total 2828
telemt_me_reader_eof_total 2978
telemt_me_idle_close_by_peer_total 2978
telemt_me_route_drop_no_conn_total 31272
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70200
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 303
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2879
telemt_me_writer_restored_same_endpoint_total 2810
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 70129
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 1505424584 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 33410987704 (31.12 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 15188.3 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35900
telemt_connections_bad_total 451
telemt_handshake_timeouts_total 734
telemt_upstream_connect_attempt_total 4254
telemt_upstream_connect_success_total 4221
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 4254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 5993
telemt_me_reconnect_success_total 3421
telemt_me_reader_eof_total 3625
telemt_me_idle_close_by_peer_total 3625
telemt_me_route_drop_no_conn_total 18401
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33432
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3552
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 3416
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 33414
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 432314648 (412.29 MB)
telemt_user_octets_to_client{user="hello"} 13511657596 (12.58 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 15192.7 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36975
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 1683
telemt_upstream_connect_attempt_total 5933
telemt_upstream_connect_success_total 5876
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 5933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 102614
telemt_me_reconnect_success_total 4760
telemt_me_reader_eof_total 5066
telemt_me_idle_close_by_peer_total 5066
telemt_me_route_drop_no_conn_total 13732
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32634
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 5016
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 4722
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 32917
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 2800140017 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 16465593454 (15.33 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 15197.6 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47656
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 295
telemt_upstream_connect_attempt_total 3947
telemt_upstream_connect_success_total 3928
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 3157
telemt_me_reconnect_success_total 3137
telemt_me_reader_eof_total 3262
telemt_me_idle_close_by_peer_total 3262
telemt_me_route_drop_no_conn_total 22430
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45245
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 405
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 303
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 3168
telemt_me_writer_restored_same_endpoint_total 3135
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 45124
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 547454584 (522.09 MB)
telemt_user_octets_to_client{user="hello"} 14914692640 (13.89 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 15190.6 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34263
telemt_connections_bad_total 2967
telemt_handshake_timeouts_total 1638
telemt_upstream_connect_attempt_total 3447
telemt_upstream_connect_success_total 3408
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 3446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 9132
telemt_me_reconnect_success_total 2609
telemt_me_reader_eof_total 2884
telemt_me_idle_close_by_peer_total 2884
telemt_me_route_drop_no_conn_total 11861
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28082
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 115
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2833
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 2605
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 28076
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 257692576 (245.75 MB)
telemt_user_octets_to_client{user="hello"} 7794615236 (7.26 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 15190.3 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124178
telemt_connections_bad_total 6968
telemt_handshake_timeouts_total 1371
telemt_upstream_connect_attempt_total 3160
telemt_upstream_connect_success_total 3098
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 3160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1558
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 7294
telemt_me_reconnect_success_total 2297
telemt_me_reader_eof_total 2501
telemt_me_idle_close_by_peer_total 2501
telemt_me_route_drop_no_conn_total 63092
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110213
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2473
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2293
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 109582
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 2552917784 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 54628791620 (50.88 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 77
```