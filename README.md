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

# Server Metrics 2026-03-18 15:07:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 23182.6 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 867382
telemt_connections_bad_total 65593
telemt_handshake_timeouts_total 24027
telemt_upstream_connect_attempt_total 67267
telemt_upstream_connect_success_total 66294
telemt_upstream_connect_fail_total 973
telemt_upstream_connect_attempts_per_request{bucket="1"} 67267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 973
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 520007
telemt_me_reconnect_success_total 3140
telemt_me_reader_eof_total 3478
telemt_me_idle_close_by_peer_total 3476
telemt_me_route_drop_no_conn_total 470457
telemt_me_route_drop_channel_closed_total 184
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 662451
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3012
telemt_desync_full_logged_total 1040
telemt_desync_suppressed_total 1972
telemt_desync_frames_bucket_total{bucket="1_2"} 846
telemt_desync_frames_bucket_total{bucket="3_10"} 1010
telemt_desync_frames_bucket_total{bucket="gt_10"} 1156
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3482
telemt_me_refill_failed_total 16834
telemt_me_writer_restored_same_endpoint_total 3034
telemt_me_writer_restored_fallback_total 106
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 342
telemt_user_connections_total{user="hello"} 720523
telemt_user_connections_current{user="hello"} 1733
telemt_user_octets_from_client{user="hello"} 10751299604 (10.01 GB)
telemt_user_octets_to_client{user="hello"} 189914437733 (176.87 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 568
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 3751.1 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429277
telemt_connections_bad_total 22589
telemt_connections_current 4169
telemt_connections_me_current 4169
telemt_handshake_timeouts_total 9027
telemt_upstream_connect_attempt_total 612
telemt_upstream_connect_success_total 608
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 370
telemt_me_reconnect_success_total 364
telemt_me_reader_eof_total 270
telemt_me_idle_close_by_peer_total 269
telemt_me_route_drop_no_conn_total 381650
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378623
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1032
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 733
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 416
telemt_desync_frames_bucket_total{bucket="gt_10"} 382
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 284
telemt_me_writer_restored_same_endpoint_total 362
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 377863
telemt_user_connections_current{user="hello"} 4169
telemt_user_octets_from_client{user="hello"} 3577770372 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 102054177284 (95.05 GB)
telemt_user_unique_ips_current{user="hello"} 1283
telemt_user_unique_ips_recent_window{user="hello"} 929
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 4393.7 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451880
telemt_connections_bad_total 2761
telemt_connections_current 2987
telemt_connections_me_current 2987
telemt_handshake_timeouts_total 7019
telemt_upstream_connect_attempt_total 702
telemt_upstream_connect_success_total 699
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 452
telemt_me_reconnect_success_total 445
telemt_me_reader_eof_total 415
telemt_me_idle_close_by_peer_total 414
telemt_me_route_drop_no_conn_total 790249
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 410090
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1226
telemt_desync_full_logged_total 319
telemt_desync_suppressed_total 907
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 599
telemt_desync_frames_bucket_total{bucket="gt_10"} 393
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 424
telemt_me_writer_restored_same_endpoint_total 434
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 410059
telemt_user_connections_current{user="hello"} 2987
telemt_user_octets_from_client{user="hello"} 2885156792 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 63518001276 (59.16 GB)
telemt_user_unique_ips_current{user="hello"} 959
telemt_user_unique_ips_recent_window{user="hello"} 721
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 23053.6 (6h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1893583
telemt_connections_bad_total 160381
telemt_handshake_timeouts_total 29347
telemt_upstream_connect_attempt_total 15650
telemt_upstream_connect_success_total 15622
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 806
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2987221
telemt_me_reconnect_success_total 2776
telemt_me_reader_eof_total 2895
telemt_me_idle_close_by_peer_total 2895
telemt_me_route_drop_no_conn_total 1950810
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1567671
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4468
telemt_desync_full_logged_total 1575
telemt_desync_suppressed_total 2893
telemt_desync_frames_bucket_total{bucket="1_2"} 735
telemt_desync_frames_bucket_total{bucket="3_10"} 1736
telemt_desync_frames_bucket_total{bucket="gt_10"} 1997
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2851
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2661
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1569486
telemt_user_connections_current{user="hello"} 3164
telemt_user_octets_from_client{user="hello"} 24687167443 (22.99 GB)
telemt_user_octets_to_client{user="hello"} 522887549473 (486.98 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 524
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 3843.5 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85755
telemt_connections_bad_total 5082
telemt_connections_current 915
telemt_connections_me_current 915
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 864
telemt_upstream_connect_attempt_total 4768
telemt_upstream_connect_success_total 4761
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 330148
telemt_me_reconnect_success_total 691
telemt_me_reader_eof_total 610
telemt_me_idle_close_by_peer_total 610
telemt_me_route_drop_no_conn_total 49504
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72222
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 153
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 611
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 680
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 75988
telemt_user_connections_current{user="hello"} 915
telemt_user_octets_from_client{user="hello"} 1213921753 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 12871170149 (11.99 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 2913.1 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208081
telemt_connections_bad_total 8689
telemt_connections_current 2836
telemt_connections_me_current 2836
telemt_handshake_timeouts_total 1626
telemt_upstream_connect_attempt_total 589
telemt_upstream_connect_success_total 589
telemt_upstream_connect_attempts_per_request{bucket="1"} 589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14676
telemt_me_reconnect_success_total 386
telemt_me_reader_eof_total 280
telemt_me_idle_close_by_peer_total 280
telemt_me_route_drop_no_conn_total 175036
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181509
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 468
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 295
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 325
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 181977
telemt_user_connections_current{user="hello"} 2836
telemt_user_octets_from_client{user="hello"} 1871698968 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 62613654216 (58.31 GB)
telemt_user_unique_ips_current{user="hello"} 816
telemt_user_unique_ips_recent_window{user="hello"} 392
```