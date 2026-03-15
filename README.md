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

# Server Metrics 2026-03-15 10:02:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 42472.3 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173558
telemt_connections_bad_total 1209
telemt_handshake_timeouts_total 4054
telemt_upstream_connect_attempt_total 10672
telemt_upstream_connect_success_total 10613
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 10671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5899
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 10140
telemt_me_reconnect_success_total 8476
telemt_me_reader_eof_total 9050
telemt_me_idle_close_by_peer_total 9050
telemt_me_route_drop_no_conn_total 407256
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222584
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1290
telemt_desync_full_logged_total 518
telemt_desync_suppressed_total 772
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 563
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8606
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 8445
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 162038
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 2337920584 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 172248677820 (160.42 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 42478.8 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54951
telemt_connections_bad_total 2290
telemt_handshake_timeouts_total 3033
telemt_upstream_connect_attempt_total 11463
telemt_upstream_connect_success_total 11463
telemt_upstream_connect_attempts_per_request{bucket="1"} 11463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11621
telemt_me_reconnect_success_total 9301
telemt_me_reader_eof_total 9999
telemt_me_idle_close_by_peer_total 9999
telemt_me_route_drop_no_conn_total 26379
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47895
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9473
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9285
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 47893
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 968131236 (923.28 MB)
telemt_user_octets_to_client{user="hello"} 20353120368 (18.96 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 42471.4 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62454
telemt_connections_bad_total 629
telemt_handshake_timeouts_total 2432
telemt_upstream_connect_attempt_total 11557
telemt_upstream_connect_success_total 11556
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 9450
telemt_me_reconnect_success_total 9405
telemt_me_reader_eof_total 10129
telemt_me_idle_close_by_peer_total 10129
telemt_me_route_drop_no_conn_total 23559
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56857
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9492
telemt_me_writer_restored_same_endpoint_total 9401
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 56784
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 9258250456 (8.62 GB)
telemt_user_octets_to_client{user="hello"} 35736004912 (33.28 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 42470.9 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80286
telemt_connections_bad_total 206
telemt_handshake_timeouts_total 577
telemt_upstream_connect_attempt_total 10090
telemt_upstream_connect_success_total 10089
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7994
telemt_me_reconnect_success_total 7958
telemt_me_reader_eof_total 8503
telemt_me_idle_close_by_peer_total 8503
telemt_me_route_drop_no_conn_total 33945
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72961
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 157
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8040
telemt_me_writer_restored_same_endpoint_total 7947
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 72892
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 1433917820 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 47622954540 (44.35 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 17542.4 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29304
telemt_connections_bad_total 3293
telemt_handshake_timeouts_total 477
telemt_upstream_connect_attempt_total 5958
telemt_upstream_connect_success_total 5907
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 5958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 99247
telemt_me_reconnect_success_total 4841
telemt_me_reader_eof_total 5001
telemt_me_idle_close_by_peer_total 5001
telemt_me_route_drop_no_conn_total 9670
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24801
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 4807
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 4737
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 24941
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 391203657 (373.08 MB)
telemt_user_octets_to_client{user="hello"} 11997789619 (11.17 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 42470.2 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220797
telemt_connections_bad_total 42834
telemt_handshake_timeouts_total 1338
telemt_upstream_connect_attempt_total 9093
telemt_upstream_connect_success_total 9038
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 9093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 6933
telemt_me_reconnect_success_total 6894
telemt_me_reader_eof_total 7350
telemt_me_idle_close_by_peer_total 7350
telemt_me_route_drop_no_conn_total 95831
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170883
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6941
telemt_me_writer_restored_same_endpoint_total 6867
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 169423
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 4271093812 (3.98 GB)
telemt_user_octets_to_client{user="hello"} 85873799480 (79.98 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 70
```