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

# Server Metrics 2026-03-16 08:14:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 122412.5 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 567978
telemt_connections_bad_total 5778
telemt_handshake_timeouts_total 19987
telemt_upstream_connect_attempt_total 28557
telemt_upstream_connect_success_total 28423
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 28557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15743
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25823
telemt_me_reconnect_success_total 22388
telemt_me_reader_eof_total 23954
telemt_me_idle_close_by_peer_total 23954
telemt_me_route_drop_no_conn_total 527390
telemt_me_route_drop_channel_closed_total 84
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564009
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2733
telemt_desync_full_logged_total 1073
telemt_desync_suppressed_total 1660
telemt_desync_frames_bucket_total{bucket="1_2"} 598
telemt_desync_frames_bucket_total{bucket="3_10"} 1048
telemt_desync_frames_bucket_total{bucket="gt_10"} 1087
telemt_pool_swap_total 119
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22744
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22354
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 502827
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 9596614056 (8.94 GB)
telemt_user_octets_to_client{user="hello"} 320278545664 (298.28 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 122419.9 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228627
telemt_connections_bad_total 3157
telemt_handshake_timeouts_total 15149
telemt_upstream_connect_attempt_total 32960
telemt_upstream_connect_success_total 32885
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 32960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 644
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 34334
telemt_me_reconnect_success_total 26421
telemt_me_reader_eof_total 28302
telemt_me_idle_close_by_peer_total 28301
telemt_me_route_drop_no_conn_total 111165
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202300
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 95
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 27029
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 26405
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 608
telemt_user_connections_total{user="hello"} 201840
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 4565403957 (4.25 GB)
telemt_user_octets_to_client{user="hello"} 113528351804 (105.73 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 122411.5 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244666
telemt_connections_bad_total 5735
telemt_handshake_timeouts_total 4626
telemt_upstream_connect_attempt_total 33951
telemt_upstream_connect_success_total 33943
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 33951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 35239
telemt_me_reconnect_success_total 27835
telemt_me_reader_eof_total 29954
telemt_me_idle_close_by_peer_total 29953
telemt_me_route_drop_no_conn_total 85207
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196392
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 95
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 28337
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 27827
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 502
telemt_user_connections_total{user="hello"} 196098
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 17518617989 (16.32 GB)
telemt_user_octets_to_client{user="hello"} 113123187800 (105.35 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 122411.0 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340702
telemt_connections_bad_total 1346
telemt_handshake_timeouts_total 2983
telemt_upstream_connect_attempt_total 28382
telemt_upstream_connect_success_total 28350
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 28382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22429
telemt_me_reconnect_success_total 22290
telemt_me_reader_eof_total 23784
telemt_me_idle_close_by_peer_total 23783
telemt_me_route_drop_no_conn_total 119650
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 314052
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1127
telemt_desync_full_logged_total 387
telemt_desync_suppressed_total 740
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 479
telemt_desync_frames_bucket_total{bucket="gt_10"} 418
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 22581
telemt_me_writer_restored_same_endpoint_total 22279
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 313937
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 4953921538 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 133164107944 (124.02 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 97482.5 (27h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222387
telemt_connections_bad_total 36273
telemt_handshake_timeouts_total 3724
telemt_upstream_connect_attempt_total 27870
telemt_upstream_connect_success_total 27718
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 27870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 117191
telemt_me_reconnect_success_total 22698
telemt_me_reader_eof_total 24118
telemt_me_idle_close_by_peer_total 24118
telemt_me_route_drop_no_conn_total 69420
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176041
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 559
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 426
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 22887
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 22594
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 175661
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 2375211477 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 73511013783 (68.46 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 122410.5 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 808542
telemt_connections_bad_total 70688
telemt_handshake_timeouts_total 8373
telemt_upstream_connect_attempt_total 25652
telemt_upstream_connect_success_total 25516
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 25652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13273
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 20794
telemt_me_reconnect_success_total 19445
telemt_me_reader_eof_total 20769
telemt_me_idle_close_by_peer_total 20769
telemt_me_route_drop_no_conn_total 644710
telemt_me_route_drop_channel_closed_total 111
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 805768
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
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 19718
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19418
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 273
telemt_user_connections_total{user="hello"} 664393
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 14584841484 (13.58 GB)
telemt_user_octets_to_client{user="hello"} 399865795704 (372.40 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 78
```