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

# Server Metrics 2026-03-16 05:36:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 112912.7 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 486676
telemt_connections_bad_total 5502
telemt_handshake_timeouts_total 17595
telemt_upstream_connect_attempt_total 26863
telemt_upstream_connect_success_total 26741
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 26863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24574
telemt_me_reconnect_success_total 21145
telemt_me_reader_eof_total 22623
telemt_me_idle_close_by_peer_total 22623
telemt_me_route_drop_no_conn_total 509378
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 504568
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2466
telemt_desync_full_logged_total 982
telemt_desync_suppressed_total 1484
telemt_desync_frames_bucket_total{bucket="1_2"} 499
telemt_desync_frames_bucket_total{bucket="3_10"} 969
telemt_desync_frames_bucket_total{bucket="gt_10"} 998
telemt_pool_swap_total 109
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21480
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21111
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 443415
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 8894779948 (8.28 GB)
telemt_user_octets_to_client{user="hello"} 303030058720 (282.22 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 112919.2 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196066
telemt_connections_bad_total 3001
telemt_handshake_timeouts_total 14828
telemt_upstream_connect_attempt_total 30548
telemt_upstream_connect_success_total 30473
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 30548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 31376
telemt_me_reconnect_success_total 24464
telemt_me_reader_eof_total 26226
telemt_me_idle_close_by_peer_total 26225
telemt_me_route_drop_no_conn_total 99087
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171077
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 25018
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 24448
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 170620
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 3855414909 (3.59 GB)
telemt_user_octets_to_client{user="hello"} 89062672572 (82.95 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 112911.7 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217045
telemt_connections_bad_total 3844
telemt_handshake_timeouts_total 4178
telemt_upstream_connect_attempt_total 31703
telemt_upstream_connect_success_total 31695
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 31703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 33431
telemt_me_reconnect_success_total 26037
telemt_me_reader_eof_total 28051
telemt_me_idle_close_by_peer_total 28050
telemt_me_route_drop_no_conn_total 76914
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171775
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 68
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 26523
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 26029
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 171499
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 16589122753 (15.45 GB)
telemt_user_octets_to_client{user="hello"} 105543823052 (98.30 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 112911.4 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287332
telemt_connections_bad_total 1266
telemt_handshake_timeouts_total 2638
telemt_upstream_connect_attempt_total 26328
telemt_upstream_connect_success_total 26302
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 26328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13567
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 20830
telemt_me_reconnect_success_total 20704
telemt_me_reader_eof_total 22116
telemt_me_idle_close_by_peer_total 22115
telemt_me_route_drop_no_conn_total 104777
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 263927
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 906
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 397
telemt_desync_frames_bucket_total{bucket="gt_10"} 332
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 20962
telemt_me_writer_restored_same_endpoint_total 20693
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 263816
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 4456928764 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 116800190672 (108.78 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 87982.9 (24h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193472
telemt_connections_bad_total 34466
telemt_handshake_timeouts_total 3441
telemt_upstream_connect_attempt_total 25190
telemt_upstream_connect_success_total 25053
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 25190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 115002
telemt_me_reconnect_success_total 20524
telemt_me_reader_eof_total 21799
telemt_me_idle_close_by_peer_total 21799
telemt_me_route_drop_no_conn_total 60974
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150752
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 356
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 20688
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 20420
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 150386
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 2048168217 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 66683570071 (62.10 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 112910.5 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 728274
telemt_connections_bad_total 63334
telemt_handshake_timeouts_total 5472
telemt_upstream_connect_attempt_total 23931
telemt_upstream_connect_success_total 23803
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 23931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12396
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 19515
telemt_me_reconnect_success_total 18178
telemt_me_reader_eof_total 19414
telemt_me_idle_close_by_peer_total 19414
telemt_me_route_drop_no_conn_total 612130
telemt_me_route_drop_channel_closed_total 97
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 737904
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
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 18430
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 18151
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 596570
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 13576535112 (12.64 GB)
telemt_user_octets_to_client{user="hello"} 367254410544 (342.03 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 67
```