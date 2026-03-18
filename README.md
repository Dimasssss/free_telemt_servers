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

# Server Metrics 2026-03-18 10:16:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 5743.5 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218064
telemt_connections_bad_total 1526
telemt_handshake_timeouts_total 4510
telemt_upstream_connect_attempt_total 64126
telemt_upstream_connect_success_total 63202
telemt_upstream_connect_fail_total 924
telemt_upstream_connect_attempts_per_request{bucket="1"} 64126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3090
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 924
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 507562
telemt_me_reconnect_success_total 922
telemt_me_reader_eof_total 880
telemt_me_idle_close_by_peer_total 878
telemt_me_route_drop_no_conn_total 73290
telemt_me_route_drop_channel_closed_total 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128293
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 630
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 431
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 910
telemt_me_refill_failed_total 16516
telemt_me_writer_restored_same_endpoint_total 817
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 190165
telemt_user_connections_current{user="hello"} 1550
telemt_user_octets_from_client{user="hello"} 2287928336 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 45784937149 (42.64 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 5774.7 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512830
telemt_connections_bad_total 59551
telemt_handshake_timeouts_total 12449
telemt_upstream_connect_attempt_total 1005
telemt_upstream_connect_success_total 998
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 670
telemt_me_reconnect_success_total 650
telemt_me_reader_eof_total 624
telemt_me_idle_close_by_peer_total 624
telemt_me_route_drop_no_conn_total 215402
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 412407
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2055
telemt_desync_full_logged_total 560
telemt_desync_suppressed_total 1495
telemt_desync_frames_bucket_total{bucket="1_2"} 394
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 849
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 638
telemt_me_writer_restored_same_endpoint_total 649
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 411541
telemt_user_connections_current{user="hello"} 3653
telemt_user_octets_from_client{user="hello"} 9127765644 (8.50 GB)
telemt_user_octets_to_client{user="hello"} 153365380156 (142.83 GB)
telemt_user_unique_ips_current{user="hello"} 1111
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 5689.4 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400372
telemt_connections_bad_total 23375
telemt_handshake_timeouts_total 10227
telemt_upstream_connect_attempt_total 9425
telemt_upstream_connect_success_total 9425
telemt_upstream_connect_attempts_per_request{bucket="1"} 9425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1798
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606554
telemt_me_reconnect_success_total 881
telemt_me_reader_eof_total 861
telemt_me_idle_close_by_peer_total 860
telemt_me_route_drop_no_conn_total 195816
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297377
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 451
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 299
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 877
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 846
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 305297
telemt_user_connections_current{user="hello"} 2613
telemt_user_octets_from_client{user="hello"} 3026678175 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 113341591436 (105.56 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 764
telemt_user_unique_ips_recent_window{user="hello"} 368
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 5720.1 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 760684
telemt_connections_bad_total 8428
telemt_handshake_timeouts_total 88273
telemt_upstream_connect_attempt_total 11712
telemt_upstream_connect_success_total 11592
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 11712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2816054
telemt_me_reconnect_success_total 974
telemt_me_reader_eof_total 1101
telemt_me_idle_close_by_peer_total 1101
telemt_me_route_drop_no_conn_total 1389073
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 590714
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 849
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 596
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 294
telemt_me_writer_removed_unexpected_total 1133
telemt_me_refill_failed_total 99709
telemt_me_writer_restored_same_endpoint_total 879
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 609659
telemt_user_connections_current{user="hello"} 2757
telemt_user_octets_from_client{user="hello"} 4338516902 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 76977666397 (71.69 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 819
telemt_user_unique_ips_recent_window{user="hello"} 411
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 5614.7 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393057
telemt_connections_bad_total 10998
telemt_handshake_timeouts_total 6275
telemt_upstream_connect_attempt_total 10669
telemt_upstream_connect_success_total 10668
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2982780
telemt_me_reconnect_success_total 830
telemt_me_reader_eof_total 783
telemt_me_idle_close_by_peer_total 783
telemt_me_route_drop_no_conn_total 171826
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324134
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1116
telemt_desync_full_logged_total 382
telemt_desync_suppressed_total 734
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 419
telemt_desync_frames_bucket_total{bucket="gt_10"} 513
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 783
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 715
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 332545
telemt_user_connections_current{user="hello"} 3189
telemt_user_octets_from_client{user="hello"} 5589502237 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 131347285541 (122.33 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 965
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 5499.7 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117823
telemt_connections_bad_total 15623
telemt_handshake_timeouts_total 694
telemt_upstream_connect_attempt_total 1039
telemt_upstream_connect_success_total 1039
telemt_upstream_connect_attempts_per_request{bucket="1"} 1039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 478
telemt_me_reconnect_attempts_total 699
telemt_me_reconnect_success_total 692
telemt_me_reader_eof_total 678
telemt_me_idle_close_by_peer_total 678
telemt_me_route_drop_no_conn_total 51813
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94189
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 205
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 128
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 687
telemt_me_writer_restored_same_endpoint_total 684
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 91788
telemt_user_connections_current{user="hello"} 902
telemt_user_octets_from_client{user="hello"} 1517204004 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 19755706544 (18.40 GB)
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 5570.8 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288555
telemt_connections_bad_total 19375
telemt_handshake_timeouts_total 5379
telemt_upstream_connect_attempt_total 1098
telemt_upstream_connect_success_total 1079
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 742
telemt_me_reconnect_success_total 729
telemt_me_reader_eof_total 711
telemt_me_idle_close_by_peer_total 711
telemt_me_route_drop_no_conn_total 163016
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244063
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 831
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 542
telemt_desync_frames_bucket_total{bucket="1_2"} 160
telemt_desync_frames_bucket_total{bucket="3_10"} 316
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 721
telemt_me_writer_restored_same_endpoint_total 719
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 243889
telemt_user_connections_current{user="hello"} 2188
telemt_user_octets_from_client{user="hello"} 3653193764 (3.40 GB)
telemt_user_octets_to_client{user="hello"} 117209651880 (109.16 GB)
telemt_user_unique_ips_current{user="hello"} 671
telemt_user_unique_ips_recent_window{user="hello"} 326
```