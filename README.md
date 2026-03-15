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

# Server Metrics 2026-03-15 17:06:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 67893.6 (18h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314415
telemt_connections_bad_total 2800
telemt_handshake_timeouts_total 9206
telemt_upstream_connect_attempt_total 16645
telemt_upstream_connect_success_total 16558
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 16645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16549
telemt_me_reconnect_success_total 13157
telemt_me_reader_eof_total 14015
telemt_me_idle_close_by_peer_total 14015
telemt_me_route_drop_no_conn_total 456660
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350996
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1796
telemt_desync_full_logged_total 717
telemt_desync_suppressed_total 1079
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 710
telemt_desync_frames_bucket_total{bucket="gt_10"} 754
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 13403
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13123
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 290096
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 5998713704 (5.59 GB)
telemt_user_octets_to_client{user="hello"} 234323597424 (218.23 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 67900.5 (18h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123700
telemt_connections_bad_total 2824
telemt_handshake_timeouts_total 11455
telemt_upstream_connect_attempt_total 18652
telemt_upstream_connect_success_total 18652
telemt_upstream_connect_attempts_per_request{bucket="1"} 18652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 17570
telemt_me_reconnect_success_total 15207
telemt_me_reader_eof_total 16251
telemt_me_idle_close_by_peer_total 16250
telemt_me_route_drop_no_conn_total 51830
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105789
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
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15468
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15191
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 105772
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 2058574276 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 52213430476 (48.63 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 67892.6 (18h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129046
telemt_connections_bad_total 1679
telemt_handshake_timeouts_total 3139
telemt_upstream_connect_attempt_total 20169
telemt_upstream_connect_success_total 20161
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 20169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24058
telemt_me_reconnect_success_total 16703
telemt_me_reader_eof_total 17924
telemt_me_idle_close_by_peer_total 17924
telemt_me_route_drop_no_conn_total 50494
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112945
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
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 17091
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 16695
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 112839
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 10546561876 (9.82 GB)
telemt_user_octets_to_client{user="hello"} 63979732596 (59.59 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 67892.1 (18h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174179
telemt_connections_bad_total 919
telemt_handshake_timeouts_total 1077
telemt_upstream_connect_attempt_total 16274
telemt_upstream_connect_success_total 16262
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 16274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8386
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12940
telemt_me_reconnect_success_total 12859
telemt_me_reader_eof_total 13682
telemt_me_idle_close_by_peer_total 13682
telemt_me_route_drop_no_conn_total 67663
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160494
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 552
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 354
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13014
telemt_me_writer_restored_same_endpoint_total 12848
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 160407
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 3020081836 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 72856997008 (67.85 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 42963.6 (11h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106478
telemt_connections_bad_total 23135
telemt_handshake_timeouts_total 2365
telemt_upstream_connect_attempt_total 13145
telemt_upstream_connect_success_total 13071
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 13145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105183
telemt_me_reconnect_success_total 10742
telemt_me_reader_eof_total 11266
telemt_me_idle_close_by_peer_total 11266
telemt_me_route_drop_no_conn_total 36367
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78223
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
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 10799
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10638
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 78356
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 1330346057 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 31137930563 (29.00 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 67892.3 (18h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 448601
telemt_connections_bad_total 57530
telemt_handshake_timeouts_total 3702
telemt_upstream_connect_attempt_total 14785
telemt_upstream_connect_success_total 14697
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 14785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 12568
telemt_me_reconnect_success_total 11266
telemt_me_reader_eof_total 11971
telemt_me_idle_close_by_peer_total 11971
telemt_me_route_drop_no_conn_total 271656
telemt_me_route_drop_channel_closed_total 69
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 402280
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
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11426
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11239
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 370986
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 9938840672 (9.26 GB)
telemt_user_octets_to_client{user="hello"} 196976002336 (183.45 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 92
```