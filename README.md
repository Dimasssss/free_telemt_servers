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

# Server Metrics 2026-03-12 16:02:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 30558.2 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161980
telemt_connections_bad_total 2026
telemt_handshake_timeouts_total 4752
telemt_upstream_connect_attempt_total 7368
telemt_upstream_connect_success_total 7340
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 7368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 282
telemt_me_reconnect_attempts_total 5823
telemt_me_reconnect_success_total 5781
telemt_me_reader_eof_total 6083
telemt_me_idle_close_by_peer_total 6082
telemt_me_route_drop_no_conn_total 47086
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139377
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 606
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 379
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5836
telemt_me_writer_restored_same_endpoint_total 5765
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 139343
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 2342096664 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 53949053136 (50.24 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 30451.1 (8h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67938
telemt_connections_bad_total 457
telemt_handshake_timeouts_total 496
telemt_upstream_connect_attempt_total 9795
telemt_upstream_connect_success_total 9588
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 9795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 256
telemt_me_reconnect_attempts_total 27411
telemt_me_reconnect_success_total 8052
telemt_me_reader_eof_total 8813
telemt_me_idle_close_by_peer_total 8813
telemt_me_route_drop_no_conn_total 29963
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64607
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 8711
telemt_me_refill_failed_total 604
telemt_me_writer_restored_same_endpoint_total 8037
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 659
telemt_user_connections_total{user="hello"} 64598
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 719903528 (686.55 MB)
telemt_user_octets_to_client{user="hello"} 18317375028 (17.06 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 30414.7 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92478
telemt_connections_bad_total 1437
telemt_handshake_timeouts_total 1876
telemt_upstream_connect_attempt_total 8313
telemt_upstream_connect_success_total 8313
telemt_upstream_connect_attempts_per_request{bucket="1"} 8313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4293
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 6790
telemt_me_reconnect_success_total 6732
telemt_me_reader_eof_total 7125
telemt_me_idle_close_by_peer_total 7125
telemt_me_route_drop_no_conn_total 34028
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85327
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6788
telemt_me_writer_restored_same_endpoint_total 6712
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 85301
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 2160114716 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 43887611860 (40.87 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 30390.4 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126558
telemt_connections_bad_total 13037
telemt_handshake_timeouts_total 975
telemt_upstream_connect_attempt_total 7066
telemt_upstream_connect_success_total 6860
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 7066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 302
telemt_me_reconnect_attempts_total 27896
telemt_me_reconnect_success_total 5314
telemt_me_reader_eof_total 6154
telemt_me_idle_close_by_peer_total 6154
telemt_me_route_drop_no_conn_total 44262
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105900
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 370
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 257
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6081
telemt_me_refill_failed_total 704
telemt_me_writer_restored_same_endpoint_total 5306
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 767
telemt_user_connections_total{user="hello"} 105780
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 2044698280 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 45444257728 (42.32 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 30359.8 (8h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71424
telemt_connections_bad_total 5883
telemt_handshake_timeouts_total 1084
telemt_upstream_connect_attempt_total 34299
telemt_upstream_connect_success_total 33925
telemt_upstream_connect_fail_total 374
telemt_upstream_connect_attempts_per_request{bucket="1"} 34299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 374
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 41039
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4848
telemt_me_idle_close_by_peer_total 4848
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12731
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34123
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4874
telemt_me_refill_failed_total 1170
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1190
telemt_user_connections_total{user="hello"} 62818
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 550898441 (525.38 MB)
telemt_user_octets_to_client{user="hello"} 18959802131 (17.66 GB)
telemt_user_msgs_from_client{user="hello"} 461874
telemt_user_msgs_to_client{user="hello"} 1837669
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 30347.4 (8h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189422
telemt_connections_bad_total 953
telemt_handshake_timeouts_total 1502
telemt_upstream_connect_attempt_total 6415
telemt_upstream_connect_success_total 6382
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 6415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 361
telemt_me_reconnect_attempts_total 5905
telemt_me_reconnect_success_total 4840
telemt_me_reader_eof_total 5110
telemt_me_idle_close_by_peer_total 5109
telemt_me_route_drop_no_conn_total 73428
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181324
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4935
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4833
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 181278
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 3505793832 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 80680800388 (75.14 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 61
```