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

# Server Metrics 2026-03-16 02:37:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 102188.8 (28h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440289
telemt_connections_bad_total 5363
telemt_handshake_timeouts_total 14655
telemt_upstream_connect_attempt_total 24416
telemt_upstream_connect_success_total 24302
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 24416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 22653
telemt_me_reconnect_success_total 19234
telemt_me_reader_eof_total 20568
telemt_me_idle_close_by_peer_total 20568
telemt_me_route_drop_no_conn_total 497971
telemt_me_route_drop_channel_closed_total 79
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 465004
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2268
telemt_desync_full_logged_total 909
telemt_desync_suppressed_total 1359
telemt_desync_frames_bucket_total{bucket="1_2"} 452
telemt_desync_frames_bucket_total{bucket="3_10"} 885
telemt_desync_frames_bucket_total{bucket="gt_10"} 931
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 19552
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 19200
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 403862
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 8413854416 (7.84 GB)
telemt_user_octets_to_client{user="hello"} 288776781540 (268.94 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 102195.1 (28h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179892
telemt_connections_bad_total 2963
telemt_handshake_timeouts_total 14614
telemt_upstream_connect_attempt_total 27875
telemt_upstream_connect_success_total 27800
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 27875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 29221
telemt_me_reconnect_success_total 22317
telemt_me_reader_eof_total 23899
telemt_me_idle_close_by_peer_total 23898
telemt_me_route_drop_no_conn_total 90983
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155794
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 22846
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 22301
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 155340
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 3444562665 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 80820103980 (75.27 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 102187.8 (28h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197135
telemt_connections_bad_total 2525
telemt_handshake_timeouts_total 3826
telemt_upstream_connect_attempt_total 28987
telemt_upstream_connect_success_total 28979
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 28987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 31236
telemt_me_reconnect_success_total 23852
telemt_me_reader_eof_total 25675
telemt_me_idle_close_by_peer_total 25674
telemt_me_route_drop_no_conn_total 70337
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158622
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
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 24312
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 23844
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 158398
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 16412399208 (15.29 GB)
telemt_user_octets_to_client{user="hello"} 101203229616 (94.25 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 102187.6 (28h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262658
telemt_connections_bad_total 1220
telemt_handshake_timeouts_total 1681
telemt_upstream_connect_attempt_total 23946
telemt_upstream_connect_success_total 23925
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 23946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12336
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 18965
telemt_me_reconnect_success_total 18853
telemt_me_reader_eof_total 20115
telemt_me_idle_close_by_peer_total 20114
telemt_me_route_drop_no_conn_total 96147
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242818
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 879
telemt_desync_full_logged_total 310
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 380
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 19081
telemt_me_writer_restored_same_endpoint_total 18842
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 242700
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 4160774784 (3.88 GB)
telemt_user_octets_to_client{user="hello"} 110054108704 (102.50 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 77259.0 (21h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172830
telemt_connections_bad_total 30640
telemt_handshake_timeouts_total 3023
telemt_upstream_connect_attempt_total 22059
telemt_upstream_connect_success_total 21936
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 22059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 112407
telemt_me_reconnect_success_total 17939
telemt_me_reader_eof_total 19026
telemt_me_idle_close_by_peer_total 19026
telemt_me_route_drop_no_conn_total 54033
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134444
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 18079
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 17835
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 134562
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 1885558641 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 45562324643 (42.43 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 102186.7 (28h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662502
telemt_connections_bad_total 58722
telemt_handshake_timeouts_total 4984
telemt_upstream_connect_attempt_total 21674
telemt_upstream_connect_success_total 21558
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 21674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 17788
telemt_me_reconnect_success_total 16460
telemt_me_reader_eof_total 17561
telemt_me_idle_close_by_peer_total 17561
telemt_me_route_drop_no_conn_total 589275
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 691657
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 16693
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 16433
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 550335
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 12894200564 (12.01 GB)
telemt_user_octets_to_client{user="hello"} 336332004896 (313.23 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 34
```