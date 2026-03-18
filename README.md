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

# Server Metrics 2026-03-18 15:43:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1092.9 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39177
telemt_connections_bad_total 4208
telemt_handshake_timeouts_total 2082
telemt_upstream_connect_attempt_total 157
telemt_upstream_connect_success_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 72
telemt_me_reconnect_attempts_total 44
telemt_me_reconnect_success_total 44
telemt_me_reader_eof_total 25
telemt_me_idle_close_by_peer_total 25
telemt_me_route_drop_no_conn_total 13370
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30361
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 175
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 47
telemt_me_writer_restored_same_endpoint_total 33
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 30345
telemt_user_connections_current{user="hello"} 1480
telemt_user_octets_from_client{user="hello"} 392487004 (374.30 MB)
telemt_user_octets_to_client{user="hello"} 7598451500 (7.08 GB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 5921.1 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 645860
telemt_connections_bad_total 38642
telemt_connections_current 3582
telemt_connections_me_current 3582
telemt_handshake_timeouts_total 12327
telemt_upstream_connect_attempt_total 1047
telemt_upstream_connect_success_total 1041
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 710
telemt_me_reconnect_success_total 702
telemt_me_reader_eof_total 626
telemt_me_idle_close_by_peer_total 625
telemt_me_route_drop_no_conn_total 637130
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563828
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1467
telemt_desync_full_logged_total 445
telemt_desync_suppressed_total 1022
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 584
telemt_desync_frames_bucket_total{bucket="gt_10"} 568
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 630
telemt_me_writer_restored_same_endpoint_total 700
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 563047
telemt_user_connections_current{user="hello"} 3582
telemt_user_octets_from_client{user="hello"} 5326771520 (4.96 GB)
telemt_user_octets_to_client{user="hello"} 152912110436 (142.41 GB)
telemt_user_unique_ips_current{user="hello"} 1131
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 5850.0 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425932
telemt_connections_bad_total 25533
telemt_connections_current 3078
telemt_connections_me_current 3078
telemt_handshake_timeouts_total 8117
telemt_upstream_connect_attempt_total 808
telemt_upstream_connect_success_total 803
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 475
telemt_me_reconnect_success_total 469
telemt_me_reader_eof_total 480
telemt_me_idle_close_by_peer_total 480
telemt_me_route_drop_no_conn_total 239595
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366332
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1172
telemt_desync_full_logged_total 340
telemt_desync_suppressed_total 832
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 478
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 482
telemt_me_writer_restored_same_endpoint_total 452
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 366292
telemt_user_connections_current{user="hello"} 3078
telemt_user_octets_from_client{user="hello"} 7390195732 (6.88 GB)
telemt_user_octets_to_client{user="hello"} 137962522592 (128.49 GB)
telemt_user_unique_ips_current{user="hello"} 982
telemt_user_unique_ips_recent_window{user="hello"} 412
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 6563.8 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618691
telemt_connections_bad_total 6760
telemt_connections_current 2518
telemt_connections_me_current 2518
telemt_handshake_timeouts_total 8495
telemt_upstream_connect_attempt_total 1102
telemt_upstream_connect_success_total 1093
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 714
telemt_me_reconnect_success_total 706
telemt_me_reader_eof_total 691
telemt_me_idle_close_by_peer_total 690
telemt_me_route_drop_no_conn_total 1068657
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563297
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2036
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 1539
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 940
telemt_desync_frames_bucket_total{bucket="gt_10"} 651
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 689
telemt_me_writer_restored_same_endpoint_total 695
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 563298
telemt_user_connections_current{user="hello"} 2518
telemt_user_octets_from_client{user="hello"} 3892555472 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 99043862244 (92.24 GB)
telemt_user_unique_ips_current{user="hello"} 794
telemt_user_unique_ips_recent_window{user="hello"} 385
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1078.6 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84526
telemt_connections_bad_total 13612
telemt_handshake_timeouts_total 1175
telemt_upstream_connect_attempt_total 210
telemt_upstream_connect_success_total 204
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 93
telemt_me_reconnect_success_total 92
telemt_me_reader_eof_total 59
telemt_me_idle_close_by_peer_total 59
telemt_me_route_drop_no_conn_total 26988
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63912
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 154
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 80
telemt_me_writer_restored_same_endpoint_total 66
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_user_connections_total{user="hello"} 63786
telemt_user_connections_current{user="hello"} 2881
telemt_user_octets_from_client{user="hello"} 1266565992 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 22296049480 (20.76 GB)
telemt_user_unique_ips_current{user="hello"} 976
telemt_user_unique_ips_recent_window{user="hello"} 415
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 6012.7 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121257
telemt_connections_bad_total 5679
telemt_connections_current 936
telemt_connections_me_current 936
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1145
telemt_upstream_connect_attempt_total 5136
telemt_upstream_connect_success_total 5129
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 5136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2162
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 330429
telemt_me_reconnect_success_total 972
telemt_me_reader_eof_total 902
telemt_me_idle_close_by_peer_total 902
telemt_me_route_drop_no_conn_total 69225
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105212
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 204
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 897
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 961
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 108967
telemt_user_connections_current{user="hello"} 936
telemt_user_octets_from_client{user="hello"} 1723807405 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 22060075701 (20.55 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 5083.1 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331063
telemt_connections_bad_total 13727
telemt_connections_current 2675
telemt_connections_me_current 2675
telemt_handshake_timeouts_total 3343
telemt_upstream_connect_attempt_total 920
telemt_upstream_connect_success_total 920
telemt_upstream_connect_attempts_per_request{bucket="1"} 920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14918
telemt_me_reconnect_success_total 627
telemt_me_reader_eof_total 532
telemt_me_idle_close_by_peer_total 532
telemt_me_route_drop_no_conn_total 228984
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285312
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 700
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 435
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 304
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 541
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 566
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 285609
telemt_user_connections_current{user="hello"} 2675
telemt_user_octets_from_client{user="hello"} 3906642920 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 115945442432 (107.98 GB)
telemt_user_unique_ips_current{user="hello"} 804
telemt_user_unique_ips_recent_window{user="hello"} 376
```