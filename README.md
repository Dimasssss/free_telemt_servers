# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-20 00:43:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 26730.1 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519437
telemt_connections_bad_total 33647
telemt_connections_current 785
telemt_connections_me_current 785
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 7554
telemt_upstream_connect_attempt_total 5747
telemt_upstream_connect_success_total 5671
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 5747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3242
telemt_me_reconnect_success_total 3212
telemt_me_reader_eof_total 3378
telemt_me_idle_close_by_peer_total 3377
telemt_me_route_drop_no_conn_total 152318
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413176
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2027
telemt_desync_full_logged_total 728
telemt_desync_suppressed_total 1299
telemt_desync_frames_bucket_total{bucket="1_2"} 415
telemt_desync_frames_bucket_total{bucket="3_10"} 683
telemt_desync_frames_bucket_total{bucket="gt_10"} 929
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3229
telemt_me_writer_restored_same_endpoint_total 3199
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 414607
telemt_user_connections_current{user="hello"} 785
telemt_user_octets_from_client{user="hello"} 29406253720 (27.39 GB)
telemt_user_octets_to_client{user="hello"} 149756918341 (139.47 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 43185.0 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2946124
telemt_connections_bad_total 125378
telemt_connections_current 1285
telemt_connections_me_current 1285
telemt_handshake_timeouts_total 63714
telemt_upstream_connect_attempt_total 8647
telemt_upstream_connect_success_total 8506
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 8647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9374
telemt_me_reconnect_success_total 5135
telemt_me_reader_eof_total 5494
telemt_me_idle_close_by_peer_total 5494
telemt_me_route_drop_no_conn_total 1488387
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2521021
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10896
telemt_desync_full_logged_total 3588
telemt_desync_suppressed_total 7308
telemt_desync_frames_bucket_total{bucket="1_2"} 2058
telemt_desync_frames_bucket_total{bucket="3_10"} 4274
telemt_desync_frames_bucket_total{bucket="gt_10"} 4564
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5321
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5080
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 2520836
telemt_user_connections_current{user="hello"} 1285
telemt_user_octets_from_client{user="hello"} 38900147890 (36.23 GB)
telemt_user_octets_to_client{user="hello"} 917570474698 (854.55 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 589
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 43163.1 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2879989
telemt_connections_bad_total 469852
telemt_connections_current 1097
telemt_connections_me_current 1097
telemt_handshake_timeouts_total 40804
telemt_upstream_connect_attempt_total 6856
telemt_upstream_connect_success_total 6806
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 6856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5595
telemt_me_reconnect_success_total 4663
telemt_me_reader_eof_total 4882
telemt_me_idle_close_by_peer_total 4881
telemt_me_route_drop_no_conn_total 1905049
telemt_me_route_drop_channel_closed_total 172
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1994945
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7589
telemt_desync_full_logged_total 2297
telemt_desync_suppressed_total 5292
telemt_desync_frames_bucket_total{bucket="1_2"} 1869
telemt_desync_frames_bucket_total{bucket="3_10"} 2894
telemt_desync_frames_bucket_total{bucket="gt_10"} 2826
telemt_pool_swap_total 41
telemt_me_writer_close_signal_drop_total 69
telemt_me_writer_removed_unexpected_total 4709
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4662
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1990638
telemt_user_connections_current{user="hello"} 1097
telemt_user_octets_from_client{user="hello"} 29596941644 (27.56 GB)
telemt_user_octets_to_client{user="hello"} 758358479028 (706.28 GB)
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 43150.8 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2497634
telemt_connections_bad_total 108778
telemt_connections_current 1066
telemt_connections_me_current 1066
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30470
telemt_upstream_connect_attempt_total 53828
telemt_upstream_connect_success_total 49646
telemt_upstream_connect_fail_total 4182
telemt_upstream_connect_attempts_per_request{bucket="1"} 53828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7123
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 522
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4182
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7963
telemt_me_reconnect_success_total 5183
telemt_me_reader_eof_total 5384
telemt_me_idle_close_by_peer_total 5383
telemt_me_route_drop_no_conn_total 1854589
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2099108
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8239
telemt_desync_full_logged_total 2599
telemt_desync_suppressed_total 5640
telemt_desync_frames_bucket_total{bucket="1_2"} 2024
telemt_desync_frames_bucket_total{bucket="3_10"} 2993
telemt_desync_frames_bucket_total{bucket="gt_10"} 3222
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 404
telemt_me_writer_removed_unexpected_total 5768
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5179
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 2140258
telemt_user_connections_current{user="hello"} 1066
telemt_user_octets_from_client{user="hello"} 35179969511 (32.76 GB)
telemt_user_octets_to_client{user="hello"} 599976855987 (558.77 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 96874.2 (26h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6218687
telemt_connections_bad_total 1039794
telemt_connections_current 1309
telemt_connections_me_current 1309
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 112009
telemt_upstream_connect_attempt_total 126841
telemt_upstream_connect_success_total 93558
telemt_upstream_connect_fail_total 33283
telemt_upstream_connect_attempts_per_request{bucket="1"} 126841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1430
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33283
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78075
telemt_me_reconnect_success_total 12407
telemt_me_reader_eof_total 13370
telemt_me_idle_close_by_peer_total 13356
telemt_me_route_drop_no_conn_total 2782312
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4399090
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19363
telemt_desync_full_logged_total 6119
telemt_desync_suppressed_total 13244
telemt_desync_frames_bucket_total{bucket="1_2"} 3385
telemt_desync_frames_bucket_total{bucket="3_10"} 7955
telemt_desync_frames_bucket_total{bucket="gt_10"} 8023
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 12711
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12382
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 4474305
telemt_user_connections_current{user="hello"} 1309
telemt_user_octets_from_client{user="hello"} 69696660008 (64.91 GB)
telemt_user_octets_to_client{user="hello"} 1726895216256 (1.57 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 525
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 43114.0 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 692796
telemt_connections_bad_total 71572
telemt_connections_current 317
telemt_connections_me_current 317
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12930
telemt_upstream_connect_attempt_total 12924
telemt_upstream_connect_success_total 12594
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 12924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6559
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6105
telemt_me_reconnect_success_total 6000
telemt_me_reader_eof_total 6281
telemt_me_idle_close_by_peer_total 6278
telemt_me_route_drop_no_conn_total 463500
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 570431
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6055
telemt_me_writer_restored_same_endpoint_total 5991
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 558575
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 7173042639 (6.68 GB)
telemt_user_octets_to_client{user="hello"} 136658085854 (127.27 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 43115.5 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1984216
telemt_connections_bad_total 118861
telemt_connections_current 1046
telemt_connections_me_current 1046
telemt_handshake_timeouts_total 36720
telemt_upstream_connect_attempt_total 7571
telemt_upstream_connect_success_total 7515
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 7571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5403
telemt_me_reconnect_success_total 5364
telemt_me_reader_eof_total 5656
telemt_me_idle_close_by_peer_total 5656
telemt_me_route_drop_no_conn_total 733276
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1709684
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9039
telemt_desync_full_logged_total 2899
telemt_desync_suppressed_total 6140
telemt_desync_frames_bucket_total{bucket="1_2"} 1676
telemt_desync_frames_bucket_total{bucket="3_10"} 3185
telemt_desync_frames_bucket_total{bucket="gt_10"} 4178
telemt_pool_swap_total 42
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 5447
telemt_me_writer_restored_same_endpoint_total 5347
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 1708800
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 29389897960 (27.37 GB)
telemt_user_octets_to_client{user="hello"} 866407586852 (806.90 GB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 68
```