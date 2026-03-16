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

# Server Metrics 2026-03-16 12:24:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 137422.5 (38h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 760550
telemt_connections_bad_total 54187
telemt_handshake_timeouts_total 24373
telemt_upstream_connect_attempt_total 31740
telemt_upstream_connect_success_total 31586
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 31740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17450
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 38995
telemt_me_reconnect_success_total 24764
telemt_me_reader_eof_total 26708
telemt_me_idle_close_by_peer_total 26708
telemt_me_route_drop_no_conn_total 610163
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 700585
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3357
telemt_desync_full_logged_total 1261
telemt_desync_suppressed_total 2096
telemt_desync_frames_bucket_total{bucket="1_2"} 704
telemt_desync_frames_bucket_total{bucket="3_10"} 1396
telemt_desync_frames_bucket_total{bucket="gt_10"} 1257
telemt_pool_swap_total 124
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25476
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 24729
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 712
telemt_user_connections_total{user="hello"} 637065
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 12251784832 (11.41 GB)
telemt_user_octets_to_client{user="hello"} 368338532804 (343.04 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 137429.7 (38h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316169
telemt_connections_bad_total 4386
telemt_handshake_timeouts_total 20689
telemt_upstream_connect_attempt_total 36714
telemt_upstream_connect_success_total 36607
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 36714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19950
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 838
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 43096
telemt_me_reconnect_success_total 29156
telemt_me_reader_eof_total 31329
telemt_me_idle_close_by_peer_total 31328
telemt_me_route_drop_no_conn_total 149932
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279387
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 30009
telemt_me_refill_failed_total 426
telemt_me_writer_restored_same_endpoint_total 29140
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 853
telemt_user_connections_total{user="hello"} 279080
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 5561340405 (5.18 GB)
telemt_user_octets_to_client{user="hello"} 138850028800 (129.31 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 137422.2 (38h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304268
telemt_connections_bad_total 5974
telemt_handshake_timeouts_total 8950
telemt_upstream_connect_attempt_total 38019
telemt_upstream_connect_success_total 38011
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 38019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 38549
telemt_me_reconnect_success_total 31109
telemt_me_reader_eof_total 33401
telemt_me_idle_close_by_peer_total 33400
telemt_me_route_drop_no_conn_total 103430
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249342
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 31657
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 31101
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 548
telemt_user_connections_total{user="hello"} 248940
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 18925170957 (17.63 GB)
telemt_user_octets_to_client{user="hello"} 130181576688 (121.24 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 137421.8 (38h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459388
telemt_connections_bad_total 1492
telemt_handshake_timeouts_total 5235
telemt_upstream_connect_attempt_total 31767
telemt_upstream_connect_success_total 31722
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 31767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16219
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 29882
telemt_me_reconnect_success_total 24878
telemt_me_reader_eof_total 26644
telemt_me_idle_close_by_peer_total 26643
telemt_me_route_drop_no_conn_total 155801
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424309
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1536
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1023
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 661
telemt_desync_frames_bucket_total{bucket="gt_10"} 568
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 25368
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 24867
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 424140
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 6604203342 (6.15 GB)
telemt_user_octets_to_client{user="hello"} 161575027108 (150.48 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 112493.2 (31h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287597
telemt_connections_bad_total 52600
telemt_handshake_timeouts_total 4514
telemt_upstream_connect_attempt_total 32031
telemt_upstream_connect_success_total 31860
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 32031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 121712
telemt_me_reconnect_success_total 26101
telemt_me_reader_eof_total 27715
telemt_me_idle_close_by_peer_total 27715
telemt_me_route_drop_no_conn_total 86347
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221602
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 26364
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 25997
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 221220
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 2872207769 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 98977007363 (92.18 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 137421.2 (38h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 989344
telemt_connections_bad_total 77623
telemt_handshake_timeouts_total 12392
telemt_upstream_connect_attempt_total 29079
telemt_upstream_connect_success_total 28927
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 29079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 24686
telemt_me_reconnect_success_total 22060
telemt_me_reader_eof_total 23532
telemt_me_idle_close_by_peer_total 23531
telemt_me_route_drop_no_conn_total 712051
telemt_me_route_drop_channel_closed_total 137
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 963073
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 661
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 459
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 22414
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 22033
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 354
telemt_user_connections_total{user="hello"} 821659
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 17642757556 (16.43 GB)
telemt_user_octets_to_client{user="hello"} 470016188108 (437.74 GB)
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 99
```