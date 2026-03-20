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

# Server Metrics 2026-03-20 05:03:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 42332.4 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 797407
telemt_connections_bad_total 53344
telemt_connections_current 1339
telemt_connections_me_current 1339
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18256
telemt_upstream_connect_attempt_total 8334
telemt_upstream_connect_success_total 8238
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 8334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5073
telemt_me_reconnect_success_total 5030
telemt_me_reader_eof_total 5326
telemt_me_idle_close_by_peer_total 5325
telemt_me_route_drop_no_conn_total 223020
telemt_me_route_drop_channel_closed_total 72
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 639645
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3429
telemt_desync_full_logged_total 1226
telemt_desync_suppressed_total 2203
telemt_desync_frames_bucket_total{bucket="1_2"} 663
telemt_desync_frames_bucket_total{bucket="3_10"} 1339
telemt_desync_frames_bucket_total{bucket="gt_10"} 1427
telemt_pool_swap_total 46
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 5079
telemt_me_writer_restored_same_endpoint_total 5017
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 641137
telemt_user_connections_current{user="hello"} 1339
telemt_user_octets_from_client{user="hello"} 32366442600 (30.14 GB)
telemt_user_octets_to_client{user="hello"} 218897843081 (203.86 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 58788.0 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3625838
telemt_connections_bad_total 312375
telemt_connections_current 3447
telemt_connections_me_current 3447
telemt_handshake_timeouts_total 77689
telemt_upstream_connect_attempt_total 11191
telemt_upstream_connect_success_total 10985
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 11191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11078
telemt_me_reconnect_success_total 6828
telemt_me_reader_eof_total 7305
telemt_me_idle_close_by_peer_total 7305
telemt_me_route_drop_no_conn_total 1641363
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2978906
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12338
telemt_desync_full_logged_total 4128
telemt_desync_suppressed_total 8210
telemt_desync_frames_bucket_total{bucket="1_2"} 2344
telemt_desync_frames_bucket_total{bucket="3_10"} 4791
telemt_desync_frames_bucket_total{bucket="gt_10"} 5203
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 56
telemt_me_writer_removed_unexpected_total 7044
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6773
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 2978633
telemt_user_connections_current{user="hello"} 3447
telemt_user_octets_from_client{user="hello"} 45283112562 (42.17 GB)
telemt_user_octets_to_client{user="hello"} 1130106458554 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1271
telemt_user_unique_ips_recent_window{user="hello"} 486
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 58766.2 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3303086
telemt_connections_bad_total 490865
telemt_connections_current 2888
telemt_connections_me_current 2888
telemt_handshake_timeouts_total 51797
telemt_upstream_connect_attempt_total 9558
telemt_upstream_connect_success_total 9493
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7504
telemt_me_reconnect_success_total 6563
telemt_me_reader_eof_total 6913
telemt_me_idle_close_by_peer_total 6912
telemt_me_route_drop_no_conn_total 2026995
telemt_me_route_drop_channel_closed_total 182
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2320333
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8582
telemt_desync_full_logged_total 2650
telemt_desync_suppressed_total 5932
telemt_desync_frames_bucket_total{bucket="1_2"} 2131
telemt_desync_frames_bucket_total{bucket="3_10"} 3270
telemt_desync_frames_bucket_total{bucket="gt_10"} 3181
telemt_pool_swap_total 59
telemt_me_writer_close_signal_drop_total 74
telemt_me_writer_removed_unexpected_total 6633
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6562
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 2315375
telemt_user_connections_current{user="hello"} 2888
telemt_user_octets_from_client{user="hello"} 35153275576 (32.74 GB)
telemt_user_octets_to_client{user="hello"} 934520398828 (870.34 GB)
telemt_user_unique_ips_current{user="hello"} 1020
telemt_user_unique_ips_recent_window{user="hello"} 360
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 58753.9 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2996106
telemt_connections_bad_total 224991
telemt_connections_current 2887
telemt_connections_me_current 2887
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 39514
telemt_upstream_connect_attempt_total 63542
telemt_upstream_connect_success_total 58981
telemt_upstream_connect_fail_total 4561
telemt_upstream_connect_attempts_per_request{bucket="1"} 63542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 551
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4561
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9844
telemt_me_reconnect_success_total 6909
telemt_me_reader_eof_total 7215
telemt_me_idle_close_by_peer_total 7214
telemt_me_route_drop_no_conn_total 2023028
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2433305
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9302
telemt_desync_full_logged_total 2967
telemt_desync_suppressed_total 6335
telemt_desync_frames_bucket_total{bucket="1_2"} 2237
telemt_desync_frames_bucket_total{bucket="3_10"} 3426
telemt_desync_frames_bucket_total{bucket="gt_10"} 3639
telemt_pool_swap_total 46
telemt_me_writer_close_signal_drop_total 541
telemt_me_writer_removed_unexpected_total 7594
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6905
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 685
telemt_user_connections_total{user="hello"} 2480487
telemt_user_connections_current{user="hello"} 2887
telemt_user_octets_from_client{user="hello"} 38998750997 (36.32 GB)
telemt_user_octets_to_client{user="hello"} 746001145223 (694.77 GB)
telemt_user_msgs_from_client{user="hello"} 254085
telemt_user_msgs_to_client{user="hello"} 1776413
telemt_user_unique_ips_current{user="hello"} 954
telemt_user_unique_ips_recent_window{user="hello"} 398
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 112477.2 (31h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6753569
telemt_connections_bad_total 1186490
telemt_connections_current 3116
telemt_connections_me_current 3116
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 120107
telemt_upstream_connect_attempt_total 129507
telemt_upstream_connect_success_total 96207
telemt_upstream_connect_fail_total 33300
telemt_upstream_connect_attempts_per_request{bucket="1"} 129507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33300
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79992
telemt_me_reconnect_success_total 14313
telemt_me_reader_eof_total 15396
telemt_me_idle_close_by_peer_total 15382
telemt_me_route_drop_no_conn_total 2907016
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4761863
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
telemt_desync_total 20698
telemt_desync_full_logged_total 6575
telemt_desync_suppressed_total 14123
telemt_desync_frames_bucket_total{bucket="1_2"} 3686
telemt_desync_frames_bucket_total{bucket="3_10"} 8555
telemt_desync_frames_bucket_total{bucket="gt_10"} 8457
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 14639
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14288
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 4836926
telemt_user_connections_current{user="hello"} 3116
telemt_user_octets_from_client{user="hello"} 76502206136 (71.25 GB)
telemt_user_octets_to_client{user="hello"} 1907467815040 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 1067
telemt_user_unique_ips_recent_window{user="hello"} 408
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 58717.0 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1461336
telemt_connections_bad_total 102941
telemt_connections_current 864
telemt_connections_me_current 864
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 14121
telemt_upstream_connect_attempt_total 13771
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 473466
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
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
telemt_desync_total 1539
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 964
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1285190
telemt_user_connections_current{user="hello"} 864
telemt_user_octets_from_client{user="hello"} 8813617759 (8.21 GB)
telemt_user_octets_to_client{user="hello"} 146620977362 (136.55 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 58718.6 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2368568
telemt_connections_bad_total 153112
telemt_connections_current 2746
telemt_connections_me_current 2746
telemt_handshake_timeouts_total 43746
telemt_upstream_connect_attempt_total 10566
telemt_upstream_connect_success_total 10500
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7611
telemt_me_reconnect_success_total 7562
telemt_me_reader_eof_total 7994
telemt_me_idle_close_by_peer_total 7994
telemt_me_route_drop_no_conn_total 836833
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1989717
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10102
telemt_desync_full_logged_total 3266
telemt_desync_suppressed_total 6836
telemt_desync_frames_bucket_total{bucket="1_2"} 1982
telemt_desync_frames_bucket_total{bucket="3_10"} 3543
telemt_desync_frames_bucket_total{bucket="gt_10"} 4577
telemt_pool_swap_total 60
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7668
telemt_me_writer_restored_same_endpoint_total 7545
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 1988417
telemt_user_connections_current{user="hello"} 2746
telemt_user_octets_from_client{user="hello"} 42270019616 (39.37 GB)
telemt_user_octets_to_client{user="hello"} 1048675104048 (976.65 GB)
telemt_user_unique_ips_current{user="hello"} 948
telemt_user_unique_ips_recent_window{user="hello"} 332
```