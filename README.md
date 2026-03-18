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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 13:20:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 16748.8 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624989
telemt_connections_bad_total 26100
telemt_handshake_timeouts_total 16922
telemt_upstream_connect_attempt_total 66224
telemt_upstream_connect_success_total 65269
telemt_upstream_connect_fail_total 955
telemt_upstream_connect_attempts_per_request{bucket="1"} 66224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 955
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 514084
telemt_me_reconnect_success_total 2435
telemt_me_reader_eof_total 2595
telemt_me_idle_close_by_peer_total 2593
telemt_me_route_drop_no_conn_total 368101
telemt_me_route_drop_channel_closed_total 134
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 480122
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2168
telemt_desync_full_logged_total 725
telemt_desync_suppressed_total 1443
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 796
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2603
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2330
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 538321
telemt_user_connections_current{user="hello"} 1774
telemt_user_octets_from_client{user="hello"} 7212390516 (6.72 GB)
telemt_user_octets_to_client{user="hello"} 136481925829 (127.11 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 554
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 16779.7 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1657103
telemt_connections_bad_total 116545
telemt_handshake_timeouts_total 36762
telemt_upstream_connect_attempt_total 2989
telemt_upstream_connect_success_total 2977
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3202
telemt_me_reconnect_success_total 2060
telemt_me_reader_eof_total 2137
telemt_me_idle_close_by_peer_total 2136
telemt_me_route_drop_no_conn_total 1371119
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1424526
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4379
telemt_desync_full_logged_total 1368
telemt_desync_suppressed_total 3011
telemt_desync_frames_bucket_total{bucket="1_2"} 893
telemt_desync_frames_bucket_total{bucket="3_10"} 1778
telemt_desync_frames_bucket_total{bucket="gt_10"} 1708
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2108
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2059
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 1423519
telemt_user_connections_current{user="hello"} 4454
telemt_user_octets_from_client{user="hello"} 35447846080 (33.01 GB)
telemt_user_octets_to_client{user="hello"} 430342221740 (400.79 GB)
telemt_user_unique_ips_current{user="hello"} 1317
telemt_user_unique_ips_recent_window{user="hello"} 597
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 16725.0 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1971445
telemt_connections_bad_total 31336
telemt_handshake_timeouts_total 173611
telemt_upstream_connect_attempt_total 12551
telemt_upstream_connect_success_total 12348
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 12551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2832562
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 1804
telemt_me_idle_close_by_peer_total 1804
telemt_me_route_drop_no_conn_total 2999096
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1612729
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3365
telemt_desync_full_logged_total 1019
telemt_desync_suppressed_total 2346
telemt_desync_frames_bucket_total{bucket="1_2"} 870
telemt_desync_frames_bucket_total{bucket="3_10"} 1415
telemt_desync_frames_bucket_total{bucket="gt_10"} 1080
telemt_me_writer_removed_unexpected_total 1853
telemt_me_refill_failed_total 100218
telemt_me_writer_restored_same_endpoint_total 1085
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 673
telemt_user_connections_total{user="hello"} 1631256
telemt_user_connections_current{user="hello"} 3246
telemt_user_octets_from_client{user="hello"} 31076828982 (28.94 GB)
telemt_user_octets_to_client{user="hello"} 238169741845 (221.81 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 868
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 16619.6 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1305923
telemt_connections_bad_total 80905
telemt_handshake_timeouts_total 21907
telemt_upstream_connect_attempt_total 12399
telemt_upstream_connect_success_total 12398
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986445
telemt_me_reconnect_success_total 2011
telemt_me_reader_eof_total 2100
telemt_me_idle_close_by_peer_total 2100
telemt_me_route_drop_no_conn_total 1238953
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1097775
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3337
telemt_desync_full_logged_total 1126
telemt_desync_suppressed_total 2211
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 1310
telemt_desync_frames_bucket_total{bucket="gt_10"} 1533
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2070
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 1896
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 1097849
telemt_user_connections_current{user="hello"} 3161
telemt_user_octets_from_client{user="hello"} 16568841165 (15.43 GB)
telemt_user_octets_to_client{user="hello"} 394576031241 (367.48 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1018
telemt_user_unique_ips_recent_window{user="hello"} 518
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 16505.1 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362627
telemt_connections_bad_total 33793
telemt_handshake_timeouts_total 2653
telemt_upstream_connect_attempt_total 3056
telemt_upstream_connect_success_total 3056
telemt_upstream_connect_attempts_per_request{bucket="1"} 3056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1645
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 8590
telemt_me_reconnect_success_total 2137
telemt_me_reader_eof_total 2376
telemt_me_idle_close_by_peer_total 2375
telemt_me_route_drop_no_conn_total 208974
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310224
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 816
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2356
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 2128
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 300499
telemt_user_connections_current{user="hello"} 927
telemt_user_octets_from_client{user="hello"} 4726848172 (4.40 GB)
telemt_user_octets_to_client{user="hello"} 61098420324 (56.90 GB)
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 16575.7 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1056780
telemt_connections_bad_total 118066
telemt_handshake_timeouts_total 21491
telemt_upstream_connect_attempt_total 3072
telemt_upstream_connect_success_total 3045
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 3072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 2171
telemt_me_reconnect_success_total 2125
telemt_me_reader_eof_total 2182
telemt_me_idle_close_by_peer_total 2182
telemt_me_route_drop_no_conn_total 619988
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 834099
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2862
telemt_desync_full_logged_total 954
telemt_desync_suppressed_total 1908
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 970
telemt_desync_frames_bucket_total{bucket="gt_10"} 1371
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2146
telemt_me_writer_restored_same_endpoint_total 2115
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 833540
telemt_user_connections_current{user="hello"} 2684
telemt_user_octets_from_client{user="hello"} 16521025084 (15.39 GB)
telemt_user_octets_to_client{user="hello"} 381957651172 (355.73 GB)
telemt_user_unique_ips_current{user="hello"} 863
telemt_user_unique_ips_recent_window{user="hello"} 395
```