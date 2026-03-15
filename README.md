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

# Server Metrics 2026-03-15 16:55:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 67280.0 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310717
telemt_connections_bad_total 2799
telemt_handshake_timeouts_total 9190
telemt_upstream_connect_attempt_total 16512
telemt_upstream_connect_success_total 16427
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 16512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9128
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16461
telemt_me_reconnect_success_total 13072
telemt_me_reader_eof_total 13924
telemt_me_idle_close_by_peer_total 13924
telemt_me_route_drop_no_conn_total 455380
telemt_me_route_drop_channel_closed_total 75
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347478
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1774
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1062
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 700
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13315
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13038
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 286580
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 5969387368 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 232802887848 (216.81 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 67286.6 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122120
telemt_connections_bad_total 2823
telemt_handshake_timeouts_total 11328
telemt_upstream_connect_attempt_total 18500
telemt_upstream_connect_success_total 18500
telemt_upstream_connect_attempts_per_request{bucket="1"} 18500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10301
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 17461
telemt_me_reconnect_success_total 15098
telemt_me_reader_eof_total 16129
telemt_me_idle_close_by_peer_total 16128
telemt_me_route_drop_no_conn_total 50871
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104371
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 15357
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15082
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 104355
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 2048714752 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 51720169400 (48.17 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 67279.3 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127460
telemt_connections_bad_total 1667
telemt_handshake_timeouts_total 3128
telemt_upstream_connect_attempt_total 19999
telemt_upstream_connect_success_total 19991
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 19999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 23931
telemt_me_reconnect_success_total 16575
telemt_me_reader_eof_total 17784
telemt_me_idle_close_by_peer_total 17784
telemt_me_route_drop_no_conn_total 49757
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111439
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 16964
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 16567
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 111333
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 10482883156 (9.76 GB)
telemt_user_octets_to_client{user="hello"} 63433838640 (59.08 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 67278.8 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171786
telemt_connections_bad_total 918
telemt_handshake_timeouts_total 1065
telemt_upstream_connect_attempt_total 16121
telemt_upstream_connect_success_total 16110
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 16121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12831
telemt_me_reconnect_success_total 12751
telemt_me_reader_eof_total 13566
telemt_me_idle_close_by_peer_total 13566
telemt_me_route_drop_no_conn_total 66851
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158163
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 547
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 352
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12905
telemt_me_writer_restored_same_endpoint_total 12740
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 158076
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 2948174748 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 72053358080 (67.10 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 42350.2 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104784
telemt_connections_bad_total 23020
telemt_handshake_timeouts_total 2312
telemt_upstream_connect_attempt_total 13004
telemt_upstream_connect_success_total 12931
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 13004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105070
telemt_me_reconnect_success_total 10629
telemt_me_reader_eof_total 11138
telemt_me_idle_close_by_peer_total 11138
telemt_me_route_drop_no_conn_total 35878
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76795
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 189
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 10683
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10525
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 76930
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 1322582181 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 30892619663 (28.77 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 67280.4 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443011
telemt_connections_bad_total 57528
telemt_handshake_timeouts_total 3606
telemt_upstream_connect_attempt_total 14627
telemt_upstream_connect_success_total 14540
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 14627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 12454
telemt_me_reconnect_success_total 11152
telemt_me_reader_eof_total 11840
telemt_me_idle_close_by_peer_total 11840
telemt_me_route_drop_no_conn_total 266489
telemt_me_route_drop_channel_closed_total 64
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396615
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11310
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11125
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 365728
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 9834656548 (9.16 GB)
telemt_user_octets_to_client{user="hello"} 194523050640 (181.16 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 78
```