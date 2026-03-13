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

# Server Metrics 2026-03-13 13:38:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 108309.6 (30h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 446315
telemt_connections_bad_total 3215
telemt_handshake_timeouts_total 8484
telemt_upstream_connect_attempt_total 27383
telemt_upstream_connect_success_total 27254
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 27383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2408
telemt_me_reconnect_attempts_total 25346
telemt_me_reconnect_success_total 21819
telemt_me_reader_eof_total 23305
telemt_me_idle_close_by_peer_total 23304
telemt_me_route_drop_no_conn_total 143321
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 389525
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1313
telemt_desync_full_logged_total 466
telemt_desync_suppressed_total 847
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 479
telemt_desync_frames_bucket_total{bucket="gt_10"} 553
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 22157
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21803
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 389107
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 7083637732 (6.60 GB)
telemt_user_octets_to_client{user="hello"} 174508710508 (162.52 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 108202.7 (30h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208635
telemt_connections_bad_total 1681
telemt_handshake_timeouts_total 1519
telemt_upstream_connect_attempt_total 68566
telemt_upstream_connect_success_total 67835
telemt_upstream_connect_fail_total 731
telemt_upstream_connect_attempts_per_request{bucket="1"} 68566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 644
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 731
telemt_me_keepalive_timeout_total 1388
telemt_me_reconnect_attempts_total 103773
telemt_me_reconnect_success_total 26002
telemt_me_reader_eof_total 29192
telemt_me_idle_close_by_peer_total 29192
telemt_me_route_drop_no_conn_total 79847
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160862
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28656
telemt_me_refill_failed_total 2426
telemt_me_writer_restored_same_endpoint_total 25985
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2654
telemt_user_connections_total{user="hello"} 197054
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 2008312840 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 64004664515 (59.61 GB)
telemt_user_msgs_from_client{user="hello"} 542459
telemt_user_msgs_to_client{user="hello"} 3817776
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 108166.4 (30h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253652
telemt_connections_bad_total 2075
telemt_handshake_timeouts_total 9984
telemt_upstream_connect_attempt_total 29157
telemt_upstream_connect_success_total 29153
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 29157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15599
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2251
telemt_me_reconnect_attempts_total 24894
telemt_me_reconnect_success_total 23680
telemt_me_reader_eof_total 25371
telemt_me_idle_close_by_peer_total 25371
telemt_me_route_drop_no_conn_total 92561
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232433
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 23937
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23660
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 232350
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 9454866828 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 100131211764 (93.25 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 108141.7 (30h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351275
telemt_connections_bad_total 15034
telemt_handshake_timeouts_total 3418
telemt_upstream_connect_attempt_total 41118
telemt_upstream_connect_success_total 31001
telemt_upstream_connect_fail_total 10117
telemt_upstream_connect_attempts_per_request{bucket="1"} 41118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10117
telemt_me_keepalive_timeout_total 4128
telemt_me_reconnect_attempts_total 95293
telemt_me_reconnect_success_total 22522
telemt_me_reader_eof_total 25472
telemt_me_idle_close_by_peer_total 25465
telemt_me_route_drop_no_conn_total 125846
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302543
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1131
telemt_desync_full_logged_total 332
telemt_desync_suppressed_total 799
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 428
telemt_desync_frames_bucket_total{bucket="gt_10"} 427
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 25082
telemt_me_refill_failed_total 2269
telemt_me_writer_restored_same_endpoint_total 22512
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2560
telemt_user_connections_total{user="hello"} 305453
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 6658776738 (6.20 GB)
telemt_user_octets_to_client{user="hello"} 114540428261 (106.67 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 58313.2 (16h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87012
telemt_connections_bad_total 11554
telemt_handshake_timeouts_total 1203
telemt_upstream_connect_attempt_total 24465
telemt_upstream_connect_success_total 24268
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 24465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 1002
telemt_me_reconnect_attempts_total 26363
telemt_me_reconnect_success_total 16443
telemt_me_reader_eof_total 17651
telemt_me_idle_close_by_peer_total 17651
telemt_me_route_drop_no_conn_total 26081
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66561
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 178
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 16897
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16425
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 71461
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 872036685 (831.64 MB)
telemt_user_octets_to_client{user="hello"} 21142940663 (19.69 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 108098.2 (30h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 628945
telemt_connections_bad_total 17944
telemt_handshake_timeouts_total 17775
telemt_upstream_connect_attempt_total 22847
telemt_upstream_connect_success_total 22729
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 22847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2506
telemt_me_reconnect_attempts_total 21954
telemt_me_reconnect_success_total 17330
telemt_me_reader_eof_total 18604
telemt_me_idle_close_by_peer_total 18601
telemt_me_route_drop_no_conn_total 305893
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 599010
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 472
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 17700
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17323
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 571956
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 9992183112 (9.31 GB)
telemt_user_octets_to_client{user="hello"} 304667121080 (283.74 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 60
```