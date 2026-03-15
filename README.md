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

# Server Metrics 2026-03-15 16:50:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 66973.7 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309019
telemt_connections_bad_total 2798
telemt_handshake_timeouts_total 9185
telemt_upstream_connect_attempt_total 16465
telemt_upstream_connect_success_total 16380
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 16465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9101
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16414
telemt_me_reconnect_success_total 13025
telemt_me_reader_eof_total 13877
telemt_me_idle_close_by_peer_total 13877
telemt_me_route_drop_no_conn_total 454831
telemt_me_route_drop_channel_closed_total 75
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345868
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1773
telemt_desync_full_logged_total 711
telemt_desync_suppressed_total 1062
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 700
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13268
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12991
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 284970
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 5954662224 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 232207072148 (216.26 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 66980.4 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121219
telemt_connections_bad_total 2821
telemt_handshake_timeouts_total 11290
telemt_upstream_connect_attempt_total 18447
telemt_upstream_connect_success_total 18447
telemt_upstream_connect_attempts_per_request{bucket="1"} 18447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10269
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 17408
telemt_me_reconnect_success_total 15045
telemt_me_reader_eof_total 16075
telemt_me_idle_close_by_peer_total 16074
telemt_me_route_drop_no_conn_total 50357
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103539
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
telemt_me_writer_removed_unexpected_total 15303
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15029
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 103523
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 2043568736 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 51238959712 (47.72 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 66972.7 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126736
telemt_connections_bad_total 1665
telemt_handshake_timeouts_total 3122
telemt_upstream_connect_attempt_total 19950
telemt_upstream_connect_success_total 19942
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 19950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 23882
telemt_me_reconnect_success_total 16527
telemt_me_reader_eof_total 17735
telemt_me_idle_close_by_peer_total 17735
telemt_me_route_drop_no_conn_total 49342
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110735
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
telemt_me_writer_removed_unexpected_total 16915
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 16519
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 110630
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 10477917540 (9.76 GB)
telemt_user_octets_to_client{user="hello"} 63135927092 (58.80 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 66972.5 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170767
telemt_connections_bad_total 916
telemt_handshake_timeouts_total 1059
telemt_upstream_connect_attempt_total 16074
telemt_upstream_connect_success_total 16063
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 16074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8275
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12786
telemt_me_reconnect_success_total 12706
telemt_me_reader_eof_total 13521
telemt_me_idle_close_by_peer_total 13521
telemt_me_route_drop_no_conn_total 66513
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157180
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 545
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 352
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12860
telemt_me_writer_restored_same_endpoint_total 12695
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 157093
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 2927538352 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 71812190924 (66.88 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 42043.9 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103870
telemt_connections_bad_total 22966
telemt_handshake_timeouts_total 2301
telemt_upstream_connect_attempt_total 12938
telemt_upstream_connect_success_total 12865
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 12938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105020
telemt_me_reconnect_success_total 10579
telemt_me_reader_eof_total 11088
telemt_me_idle_close_by_peer_total 11088
telemt_me_route_drop_no_conn_total 35539
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76021
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
telemt_me_writer_removed_unexpected_total 10633
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10475
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 76156
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 1289091029 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 30742365623 (28.63 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 66972.2 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440017
telemt_connections_bad_total 57524
telemt_handshake_timeouts_total 3568
telemt_upstream_connect_attempt_total 14562
telemt_upstream_connect_success_total 14475
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 14562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 12389
telemt_me_reconnect_success_total 11087
telemt_me_reader_eof_total 11773
telemt_me_idle_close_by_peer_total 11773
telemt_me_route_drop_no_conn_total 262640
telemt_me_route_drop_channel_closed_total 64
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392667
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
telemt_me_writer_removed_unexpected_total 11243
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11060
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 362905
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 9768439396 (9.10 GB)
telemt_user_octets_to_client{user="hello"} 193042952652 (179.79 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 86
```