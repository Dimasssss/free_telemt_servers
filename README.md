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

# Server Metrics 2026-03-18 10:06:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 5133.4 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198295
telemt_connections_bad_total 1330
telemt_handshake_timeouts_total 3890
telemt_upstream_connect_attempt_total 63984
telemt_upstream_connect_success_total 63063
telemt_upstream_connect_fail_total 921
telemt_upstream_connect_attempts_per_request{bucket="1"} 63984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 921
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 507466
telemt_me_reconnect_success_total 827
telemt_me_reader_eof_total 773
telemt_me_idle_close_by_peer_total 771
telemt_me_route_drop_no_conn_total 61562
telemt_me_route_drop_channel_closed_total 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110183
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 581
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 201
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 814
telemt_me_refill_failed_total 16516
telemt_me_writer_restored_same_endpoint_total 722
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 172039
telemt_user_connections_current{user="hello"} 1581
telemt_user_octets_from_client{user="hello"} 1994828796 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 38761998813 (36.10 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 5164.8 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460562
telemt_connections_bad_total 55237
telemt_handshake_timeouts_total 11341
telemt_upstream_connect_attempt_total 877
telemt_upstream_connect_success_total 877
telemt_upstream_connect_attempts_per_request{bucket="1"} 877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 585
telemt_me_reconnect_success_total 573
telemt_me_reader_eof_total 544
telemt_me_idle_close_by_peer_total 544
telemt_me_route_drop_no_conn_total 176086
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366717
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1811
telemt_desync_full_logged_total 488
telemt_desync_suppressed_total 1323
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 704
telemt_desync_frames_bucket_total{bucket="gt_10"} 753
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 554
telemt_me_writer_restored_same_endpoint_total 572
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 365867
telemt_user_connections_current{user="hello"} 3882
telemt_user_octets_from_client{user="hello"} 8351385012 (7.78 GB)
telemt_user_octets_to_client{user="hello"} 135537720640 (126.23 GB)
telemt_user_unique_ips_current{user="hello"} 1172
telemt_user_unique_ips_recent_window{user="hello"} 646
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 5079.6 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365506
telemt_connections_bad_total 21151
telemt_handshake_timeouts_total 9213
telemt_upstream_connect_attempt_total 9278
telemt_upstream_connect_success_total 9278
telemt_upstream_connect_attempts_per_request{bucket="1"} 9278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606450
telemt_me_reconnect_success_total 778
telemt_me_reader_eof_total 746
telemt_me_idle_close_by_peer_total 745
telemt_me_route_drop_no_conn_total 179866
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269731
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 646
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 425
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 773
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 743
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 277742
telemt_user_connections_current{user="hello"} 2676
telemt_user_octets_from_client{user="hello"} 2783136119 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 103526181104 (96.42 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 789
telemt_user_unique_ips_recent_window{user="hello"} 418
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 5109.6 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 709957
telemt_connections_bad_total 8070
telemt_handshake_timeouts_total 76745
telemt_upstream_connect_attempt_total 11609
telemt_upstream_connect_success_total 11500
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 11609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1060
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2814627
telemt_me_reconnect_success_total 926
telemt_me_reader_eof_total 1015
telemt_me_idle_close_by_peer_total 1015
telemt_me_route_drop_no_conn_total 1364952
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 556559
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
telemt_desync_total 770
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 315
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_me_writer_removed_unexpected_total 1041
telemt_me_refill_failed_total 99666
telemt_me_writer_restored_same_endpoint_total 831
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 575516
telemt_user_connections_current{user="hello"} 2657
telemt_user_octets_from_client{user="hello"} 3874497194 (3.61 GB)
telemt_user_octets_to_client{user="hello"} 67527879601 (62.89 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 816
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 5004.6 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354345
telemt_connections_bad_total 10201
telemt_handshake_timeouts_total 5683
telemt_upstream_connect_attempt_total 10556
telemt_upstream_connect_success_total 10555
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2982710
telemt_me_reconnect_success_total 760
telemt_me_reader_eof_total 704
telemt_me_idle_close_by_peer_total 704
telemt_me_route_drop_no_conn_total 152731
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288920
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 923
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 601
telemt_desync_frames_bucket_total{bucket="1_2"} 142
telemt_desync_frames_bucket_total{bucket="3_10"} 352
telemt_desync_frames_bucket_total{bucket="gt_10"} 429
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 712
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 645
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 297339
telemt_user_connections_current{user="hello"} 3271
telemt_user_octets_from_client{user="hello"} 5216561757 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 115658674205 (107.72 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 956
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 4889.4 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103331
telemt_connections_bad_total 13285
telemt_handshake_timeouts_total 581
telemt_upstream_connect_attempt_total 892
telemt_upstream_connect_success_total 892
telemt_upstream_connect_attempts_per_request{bucket="1"} 892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 405
telemt_me_reconnect_attempts_total 593
telemt_me_reconnect_success_total 586
telemt_me_reader_eof_total 572
telemt_me_idle_close_by_peer_total 572
telemt_me_route_drop_no_conn_total 46945
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84278
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 175
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 581
telemt_me_writer_restored_same_endpoint_total 578
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 81882
telemt_user_connections_current{user="hello"} 884
telemt_user_octets_from_client{user="hello"} 1420482988 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 17412444380 (16.22 GB)
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 4960.5 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254017
telemt_connections_bad_total 13488
telemt_handshake_timeouts_total 4612
telemt_upstream_connect_attempt_total 930
telemt_upstream_connect_success_total 912
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 618
telemt_me_reconnect_success_total 606
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_route_drop_no_conn_total 144483
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218544
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 745
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 487
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 323
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 598
telemt_me_writer_restored_same_endpoint_total 596
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 218380
telemt_user_connections_current{user="hello"} 2468
telemt_user_octets_from_client{user="hello"} 3152229312 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 104252294148 (97.09 GB)
telemt_user_unique_ips_current{user="hello"} 698
telemt_user_unique_ips_recent_window{user="hello"} 351
```