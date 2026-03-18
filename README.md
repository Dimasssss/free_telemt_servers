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

# Server Metrics 2026-03-18 08:04:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 46.9 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_upstream_connect_attempt_total 77
telemt_upstream_connect_success_total 58
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 75
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 134588.0 (37h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2020334
telemt_connections_bad_total 107665
telemt_handshake_timeouts_total 62305
telemt_upstream_connect_attempt_total 472571
telemt_upstream_connect_success_total 470917
telemt_upstream_connect_fail_total 1654
telemt_upstream_connect_attempts_per_request{bucket="1"} 472571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35674
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1654
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 425
telemt_me_reconnect_attempts_total 134683
telemt_me_reconnect_success_total 21291
telemt_me_reader_eof_total 23814
telemt_me_idle_close_by_peer_total 23800
telemt_me_route_drop_no_conn_total 641546
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1315987
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5998
telemt_desync_full_logged_total 2076
telemt_desync_suppressed_total 3922
telemt_desync_frames_bucket_total{bucket="1_2"} 1127
telemt_desync_frames_bucket_total{bucket="3_10"} 2433
telemt_desync_frames_bucket_total{bucket="gt_10"} 2438
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 23139
telemt_me_refill_failed_total 3537
telemt_me_writer_restored_same_endpoint_total 21273
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1848
telemt_user_connections_total{user="hello"} 1758389
telemt_user_connections_current{user="hello"} 3120
telemt_user_octets_from_client{user="hello"} 29799749505 (27.75 GB)
telemt_user_octets_to_client{user="hello"} 688615473182 (641.32 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 916
telemt_user_unique_ips_recent_window{user="hello"} 533
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 134422.9 (37h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1960451
telemt_connections_bad_total 89326
telemt_handshake_timeouts_total 36995
telemt_upstream_connect_attempt_total 93451
telemt_upstream_connect_success_total 90986
telemt_upstream_connect_fail_total 2465
telemt_upstream_connect_attempts_per_request{bucket="1"} 93451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 388
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2465
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 363
telemt_me_reconnect_attempts_total 41027
telemt_me_reconnect_success_total 19492
telemt_me_reader_eof_total 21351
telemt_me_idle_close_by_peer_total 21348
telemt_me_route_drop_no_conn_total 987964
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1633513
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6413
telemt_desync_full_logged_total 1960
telemt_desync_suppressed_total 4453
telemt_desync_frames_bucket_total{bucket="1_2"} 1446
telemt_desync_frames_bucket_total{bucket="3_10"} 2633
telemt_desync_frames_bucket_total{bucket="gt_10"} 2334
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20530
telemt_me_refill_failed_total 663
telemt_me_writer_restored_same_endpoint_total 19472
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1038
telemt_user_connections_total{user="hello"} 1696592
telemt_user_connections_current{user="hello"} 3011
telemt_user_octets_from_client{user="hello"} 27010547974 (25.16 GB)
telemt_user_octets_to_client{user="hello"} 740536761754 (689.68 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 795
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 134394.8 (37h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1419975
telemt_connections_bad_total 121540
telemt_handshake_timeouts_total 16284
telemt_upstream_connect_attempt_total 50093
telemt_upstream_connect_success_total 49394
telemt_upstream_connect_fail_total 699
telemt_upstream_connect_attempts_per_request{bucket="1"} 50093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 699
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 69095
telemt_me_reconnect_success_total 26215
telemt_me_reader_eof_total 28543
telemt_me_idle_close_by_peer_total 28540
telemt_me_route_drop_no_conn_total 582265
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1178140
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5105
telemt_desync_full_logged_total 1578
telemt_desync_suppressed_total 3527
telemt_desync_frames_bucket_total{bucket="1_2"} 1300
telemt_desync_frames_bucket_total{bucket="3_10"} 1988
telemt_desync_frames_bucket_total{bucket="gt_10"} 1817
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27960
telemt_me_refill_failed_total 1334
telemt_me_writer_restored_same_endpoint_total 26207
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1745
telemt_user_connections_total{user="hello"} 1194410
telemt_user_connections_current{user="hello"} 2851
telemt_user_octets_from_client{user="hello"} 22892079080 (21.32 GB)
telemt_user_octets_to_client{user="hello"} 575352883232 (535.84 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 786
telemt_user_unique_ips_recent_window{user="hello"} 523
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 134556.6 (37h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1343426
telemt_connections_bad_total 137880
telemt_handshake_timeouts_total 11153
telemt_upstream_connect_attempt_total 26866
telemt_upstream_connect_success_total 26708
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 26866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13686
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 284
telemt_me_reconnect_attempts_total 31324
telemt_me_reconnect_success_total 20010
telemt_me_reader_eof_total 21633
telemt_me_idle_close_by_peer_total 21630
telemt_me_route_drop_no_conn_total 909421
telemt_me_route_drop_channel_closed_total 102
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1304998
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2572
telemt_desync_full_logged_total 904
telemt_desync_suppressed_total 1668
telemt_desync_frames_bucket_total{bucket="1_2"} 554
telemt_desync_frames_bucket_total{bucket="3_10"} 995
telemt_desync_frames_bucket_total{bucket="gt_10"} 1023
telemt_pool_swap_total 120
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20672
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19996
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 662
telemt_user_connections_total{user="hello"} 1113657
telemt_user_connections_current{user="hello"} 1028
telemt_user_octets_from_client{user="hello"} 16984251084 (15.82 GB)
telemt_user_octets_to_client{user="hello"} 475728579096 (443.06 GB)
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 82323.0 (22h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 811982
telemt_connections_bad_total 77965
telemt_handshake_timeouts_total 17323
telemt_upstream_connect_attempt_total 27436
telemt_upstream_connect_success_total 27125
telemt_upstream_connect_fail_total 311
telemt_upstream_connect_attempts_per_request{bucket="1"} 27436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 311
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 36837
telemt_me_reconnect_success_total 22866
telemt_me_reader_eof_total 24191
telemt_me_idle_close_by_peer_total 24191
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 249063
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 613696
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2491
telemt_desync_full_logged_total 850
telemt_desync_suppressed_total 1641
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 1023
telemt_desync_frames_bucket_total{bucket="gt_10"} 1040
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23557
telemt_me_refill_failed_total 432
telemt_me_writer_restored_same_endpoint_total 22819
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 691
telemt_user_connections_total{user="hello"} 613350
telemt_user_connections_current{user="hello"} 1837
telemt_user_octets_from_client{user="hello"} 30034709353 (27.97 GB)
telemt_user_octets_to_client{user="hello"} 434250240134 (404.43 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 556
telemt_user_unique_ips_recent_window{user="hello"} 324
```