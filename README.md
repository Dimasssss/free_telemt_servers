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

# Server Metrics 2026-03-14 03:59:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 159961.5 (44h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 621922
telemt_connections_bad_total 30504
telemt_handshake_timeouts_total 12936
telemt_upstream_connect_attempt_total 40901
telemt_upstream_connect_success_total 40696
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 40901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5547
telemt_me_reconnect_attempts_total 37023
telemt_me_reconnect_success_total 32340
telemt_me_reader_eof_total 34559
telemt_me_idle_close_by_peer_total 34558
telemt_me_route_drop_no_conn_total 202109
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526945
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1800
telemt_desync_full_logged_total 608
telemt_desync_suppressed_total 1192
telemt_desync_frames_bucket_total{bucket="1_2"} 380
telemt_desync_frames_bucket_total{bucket="3_10"} 668
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 32838
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 32320
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 526836
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 15720131458 (14.64 GB)
telemt_user_octets_to_client{user="hello"} 257173122228 (239.51 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 159854.2 (44h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314313
telemt_connections_bad_total 2266
telemt_handshake_timeouts_total 1955
telemt_upstream_connect_attempt_total 146534
telemt_upstream_connect_success_total 145362
telemt_upstream_connect_fail_total 1172
telemt_upstream_connect_attempts_per_request{bucket="1"} 146534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1172
telemt_me_keepalive_timeout_total 3863
telemt_me_reconnect_attempts_total 168397
telemt_me_reconnect_success_total 34085
telemt_me_reader_eof_total 39172
telemt_me_idle_close_by_peer_total 39172
telemt_me_route_drop_no_conn_total 99143
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194942
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 38603
telemt_me_refill_failed_total 4191
telemt_me_writer_restored_same_endpoint_total 34068
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4518
telemt_user_connections_total{user="hello"} 298054
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 3115248523 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 96670818103 (90.03 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 159818.7 (44h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367354
telemt_connections_bad_total 2914
telemt_handshake_timeouts_total 34787
telemt_upstream_connect_attempt_total 42377
telemt_upstream_connect_success_total 42371
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 42377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22938
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3331
telemt_me_reconnect_attempts_total 35640
telemt_me_reconnect_success_total 34364
telemt_me_reader_eof_total 36931
telemt_me_idle_close_by_peer_total 36931
telemt_me_route_drop_no_conn_total 131236
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316920
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 34766
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 34343
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 316732
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 12673949556 (11.80 GB)
telemt_user_octets_to_client{user="hello"} 127817065596 (119.04 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 159793.4 (44h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468712
telemt_connections_bad_total 15547
telemt_handshake_timeouts_total 4401
telemt_upstream_connect_attempt_total 72114
telemt_upstream_connect_success_total 61610
telemt_upstream_connect_fail_total 10504
telemt_upstream_connect_attempts_per_request{bucket="1"} 72114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24478
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10504
telemt_me_keepalive_timeout_total 5143
telemt_me_reconnect_attempts_total 140657
telemt_me_reconnect_success_total 34611
telemt_me_reader_eof_total 38983
telemt_me_idle_close_by_peer_total 38975
telemt_me_route_drop_no_conn_total 167075
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 397662
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 38322
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 34601
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3711
telemt_user_connections_total{user="hello"} 416492
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 9157313631 (8.53 GB)
telemt_user_octets_to_client{user="hello"} 162195976132 (151.06 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 109965.0 (30h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181824
telemt_connections_bad_total 26257
telemt_handshake_timeouts_total 1630
telemt_upstream_connect_attempt_total 39802
telemt_upstream_connect_success_total 39433
telemt_upstream_connect_fail_total 369
telemt_upstream_connect_attempts_per_request{bucket="1"} 39802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 369
telemt_me_keepalive_timeout_total 2373
telemt_me_reconnect_attempts_total 42468
telemt_me_reconnect_success_total 29048
telemt_me_reader_eof_total 31089
telemt_me_idle_close_by_peer_total 31089
telemt_me_route_drop_no_conn_total 53908
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144025
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 29730
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 29030
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 682
telemt_user_connections_total{user="hello"} 148784
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 2201753125 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 68726197511 (64.01 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 159749.4 (44h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 910540
telemt_connections_bad_total 28142
telemt_handshake_timeouts_total 25433
telemt_upstream_connect_attempt_total 33227
telemt_upstream_connect_success_total 33053
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 33227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 3511
telemt_me_reconnect_attempts_total 29812
telemt_me_reconnect_success_total 25143
telemt_me_reader_eof_total 26950
telemt_me_idle_close_by_peer_total 26947
telemt_me_route_drop_no_conn_total 433886
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 850834
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 25610
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25136
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 467
telemt_user_connections_total{user="hello"} 823499
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 14375080828 (13.39 GB)
telemt_user_octets_to_client{user="hello"} 413902967080 (385.48 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 51
```