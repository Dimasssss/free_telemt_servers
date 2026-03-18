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

# Server Metrics 2026-03-18 16:19:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3243.6 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109805
telemt_connections_bad_total 9977
telemt_handshake_timeouts_total 4078
telemt_upstream_connect_attempt_total 449
telemt_upstream_connect_success_total 449
telemt_upstream_connect_attempts_per_request{bucket="1"} 449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 250
telemt_me_reconnect_success_total 249
telemt_me_reader_eof_total 245
telemt_me_idle_close_by_peer_total 245
telemt_me_route_drop_no_conn_total 69117
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89038
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 503
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 371
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 153
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 258
telemt_me_writer_restored_same_endpoint_total 238
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 89009
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 1200062332 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 28881688848 (26.90 GB)
telemt_user_unique_ips_current{user="hello"} 494
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 8071.3 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 863517
telemt_connections_bad_total 57018
telemt_connections_current 3634
telemt_connections_me_current 3634
telemt_handshake_timeouts_total 14213
telemt_upstream_connect_attempt_total 1498
telemt_upstream_connect_success_total 1490
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1071
telemt_me_reconnect_success_total 1061
telemt_me_reader_eof_total 984
telemt_me_idle_close_by_peer_total 983
telemt_me_route_drop_no_conn_total 915172
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 750707
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2033
telemt_desync_full_logged_total 633
telemt_desync_suppressed_total 1400
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 820
telemt_desync_frames_bucket_total{bucket="gt_10"} 803
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 991
telemt_me_writer_restored_same_endpoint_total 1059
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 749891
telemt_user_connections_current{user="hello"} 3634
telemt_user_octets_from_client{user="hello"} 7277487000 (6.78 GB)
telemt_user_octets_to_client{user="hello"} 204496133296 (190.45 GB)
telemt_user_unique_ips_current{user="hello"} 1147
telemt_user_unique_ips_recent_window{user="hello"} 479
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 7999.7 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 568953
telemt_connections_bad_total 38229
telemt_connections_current 3126
telemt_connections_me_current 3126
telemt_handshake_timeouts_total 11931
telemt_upstream_connect_attempt_total 1137
telemt_upstream_connect_success_total 1132
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 524
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 712
telemt_me_reconnect_success_total 702
telemt_me_reader_eof_total 726
telemt_me_idle_close_by_peer_total 726
telemt_me_route_drop_no_conn_total 304335
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481628
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1804
telemt_desync_full_logged_total 525
telemt_desync_suppressed_total 1279
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 687
telemt_desync_frames_bucket_total{bucket="gt_10"} 707
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 722
telemt_me_writer_restored_same_endpoint_total 685
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 481348
telemt_user_connections_current{user="hello"} 3126
telemt_user_octets_from_client{user="hello"} 9129495668 (8.50 GB)
telemt_user_octets_to_client{user="hello"} 186657965300 (173.84 GB)
telemt_user_unique_ips_current{user="hello"} 1004
telemt_user_unique_ips_recent_window{user="hello"} 402
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 8713.4 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 753105
telemt_connections_bad_total 11294
telemt_connections_current 2499
telemt_connections_me_current 2499
telemt_handshake_timeouts_total 10621
telemt_upstream_connect_attempt_total 1440
telemt_upstream_connect_success_total 1429
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 961
telemt_me_reconnect_success_total 952
telemt_me_reader_eof_total 952
telemt_me_idle_close_by_peer_total 951
telemt_me_route_drop_no_conn_total 1186433
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 682922
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2705
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 2017
telemt_desync_frames_bucket_total{bucket="1_2"} 585
telemt_desync_frames_bucket_total{bucket="3_10"} 1223
telemt_desync_frames_bucket_total{bucket="gt_10"} 897
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 940
telemt_me_writer_restored_same_endpoint_total 941
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 682900
telemt_user_connections_current{user="hello"} 2499
telemt_user_octets_from_client{user="hello"} 5230469144 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 134955552296 (125.69 GB)
telemt_user_unique_ips_current{user="hello"} 830
telemt_user_unique_ips_recent_window{user="hello"} 360
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3228.9 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261170
telemt_connections_bad_total 51468
telemt_handshake_timeouts_total 3031
telemt_upstream_connect_attempt_total 602
telemt_upstream_connect_success_total 584
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 387
telemt_me_reconnect_success_total 382
telemt_me_reader_eof_total 355
telemt_me_idle_close_by_peer_total 355
telemt_me_route_drop_no_conn_total 120481
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187329
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 649
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 425
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 206
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 378
telemt_me_writer_restored_same_endpoint_total 356
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_user_connections_total{user="hello"} 187060
telemt_user_connections_current{user="hello"} 3011
telemt_user_octets_from_client{user="hello"} 2913569708 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 69895552828 (65.10 GB)
telemt_user_unique_ips_current{user="hello"} 1022
telemt_user_unique_ips_recent_window{user="hello"} 447
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 8163.4 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157591
telemt_connections_bad_total 6169
telemt_connections_current 950
telemt_connections_me_current 950
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1357
telemt_upstream_connect_attempt_total 5611
telemt_upstream_connect_success_total 5601
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 5611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 330796
telemt_me_reconnect_success_total 1336
telemt_me_reader_eof_total 1272
telemt_me_idle_close_by_peer_total 1272
telemt_me_route_drop_no_conn_total 88849
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139004
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 309
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 197
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1268
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1325
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 142736
telemt_user_connections_current{user="hello"} 950
telemt_user_octets_from_client{user="hello"} 2211638385 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 30923180093 (28.80 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 7232.6 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450406
telemt_connections_bad_total 16698
telemt_connections_current 2550
telemt_connections_me_current 2550
telemt_handshake_timeouts_total 6701
telemt_upstream_connect_attempt_total 1377
telemt_upstream_connect_success_total 1377
telemt_upstream_connect_attempts_per_request{bucket="1"} 1377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 16493
telemt_me_reconnect_success_total 984
telemt_me_reader_eof_total 928
telemt_me_idle_close_by_peer_total 928
telemt_me_route_drop_no_conn_total 300583
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388711
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1074
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 669
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 366
telemt_desync_frames_bucket_total{bucket="gt_10"} 489
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 939
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 923
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 388977
telemt_user_connections_current{user="hello"} 2550
telemt_user_octets_from_client{user="hello"} 5802028228 (5.40 GB)
telemt_user_octets_to_client{user="hello"} 165798863028 (154.41 GB)
telemt_user_unique_ips_current{user="hello"} 816
telemt_user_unique_ips_recent_window{user="hello"} 326
```