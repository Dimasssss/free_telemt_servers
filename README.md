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

# Server Metrics 2026-03-18 16:09:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2627.0 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90448
telemt_connections_bad_total 9474
telemt_handshake_timeouts_total 3551
telemt_upstream_connect_attempt_total 343
telemt_upstream_connect_success_total 343
telemt_upstream_connect_attempts_per_request{bucket="1"} 343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 187
telemt_me_reconnect_success_total 185
telemt_me_reader_eof_total 175
telemt_me_idle_close_by_peer_total 175
telemt_me_route_drop_no_conn_total 49809
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72188
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 408
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 308
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 191
telemt_me_writer_restored_same_endpoint_total 174
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 72162
telemt_user_connections_current{user="hello"} 1492
telemt_user_octets_from_client{user="hello"} 1042753600 (994.45 MB)
telemt_user_octets_to_client{user="hello"} 22147108480 (20.63 GB)
telemt_user_unique_ips_current{user="hello"} 507
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 7455.3 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814526
telemt_connections_bad_total 55049
telemt_connections_current 3458
telemt_connections_me_current 3458
telemt_handshake_timeouts_total 13886
telemt_upstream_connect_attempt_total 1382
telemt_upstream_connect_success_total 1373
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 955
telemt_me_reconnect_success_total 945
telemt_me_reader_eof_total 869
telemt_me_idle_close_by_peer_total 868
telemt_me_route_drop_no_conn_total 885153
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 707480
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1861
telemt_desync_full_logged_total 578
telemt_desync_suppressed_total 1283
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 757
telemt_desync_frames_bucket_total{bucket="gt_10"} 721
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 876
telemt_me_writer_restored_same_endpoint_total 943
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 706678
telemt_user_connections_current{user="hello"} 3458
telemt_user_octets_from_client{user="hello"} 6381326892 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 187461495792 (174.59 GB)
telemt_user_unique_ips_current{user="hello"} 1153
telemt_user_unique_ips_recent_window{user="hello"} 562
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 7384.8 (2h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 532333
telemt_connections_bad_total 36059
telemt_connections_current 3098
telemt_connections_me_current 3098
telemt_handshake_timeouts_total 10844
telemt_upstream_connect_attempt_total 1028
telemt_upstream_connect_success_total 1023
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 604
telemt_me_reconnect_success_total 596
telemt_me_reader_eof_total 618
telemt_me_idle_close_by_peer_total 618
telemt_me_route_drop_no_conn_total 288531
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 449769
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1661
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 1184
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 622
telemt_desync_frames_bucket_total{bucket="gt_10"} 656
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 614
telemt_me_writer_restored_same_endpoint_total 579
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 449502
telemt_user_connections_current{user="hello"} 3098
telemt_user_octets_from_client{user="hello"} 8587619436 (8.00 GB)
telemt_user_octets_to_client{user="hello"} 171640846316 (159.85 GB)
telemt_user_unique_ips_current{user="hello"} 959
telemt_user_unique_ips_recent_window{user="hello"} 436
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 8098.3 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 712724
telemt_connections_bad_total 9020
telemt_connections_current 2630
telemt_connections_me_current 2630
telemt_handshake_timeouts_total 9753
telemt_upstream_connect_attempt_total 1323
telemt_upstream_connect_success_total 1313
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 889
telemt_me_reconnect_success_total 880
telemt_me_reader_eof_total 869
telemt_me_idle_close_by_peer_total 868
telemt_me_route_drop_no_conn_total 1156304
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 648192
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2490
telemt_desync_full_logged_total 627
telemt_desync_suppressed_total 1863
telemt_desync_frames_bucket_total{bucket="1_2"} 535
telemt_desync_frames_bucket_total{bucket="3_10"} 1131
telemt_desync_frames_bucket_total{bucket="gt_10"} 824
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 867
telemt_me_writer_restored_same_endpoint_total 869
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 648180
telemt_user_connections_current{user="hello"} 2630
telemt_user_octets_from_client{user="hello"} 4718844624 (4.39 GB)
telemt_user_octets_to_client{user="hello"} 124830523256 (116.26 GB)
telemt_user_unique_ips_current{user="hello"} 849
telemt_user_unique_ips_recent_window{user="hello"} 369
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2612.7 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209223
telemt_connections_bad_total 39247
telemt_handshake_timeouts_total 2598
telemt_upstream_connect_attempt_total 429
telemt_upstream_connect_success_total 419
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 265
telemt_me_reconnect_success_total 262
telemt_me_reader_eof_total 232
telemt_me_idle_close_by_peer_total 232
telemt_me_route_drop_no_conn_total 96032
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151364
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 540
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 361
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 254
telemt_me_writer_restored_same_endpoint_total 236
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_user_connections_total{user="hello"} 151121
telemt_user_connections_current{user="hello"} 3022
telemt_user_octets_from_client{user="hello"} 2463279240 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 57284945232 (53.35 GB)
telemt_user_unique_ips_current{user="hello"} 1031
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 7549.3 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147374
telemt_connections_bad_total 5833
telemt_connections_current 908
telemt_connections_me_current 908
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1305
telemt_upstream_connect_attempt_total 5491
telemt_upstream_connect_success_total 5481
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 5491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 330690
telemt_me_reconnect_success_total 1231
telemt_me_reader_eof_total 1164
telemt_me_idle_close_by_peer_total 1164
telemt_me_route_drop_no_conn_total 82607
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129608
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 283
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1160
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1220
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 133352
telemt_user_connections_current{user="hello"} 908
telemt_user_octets_from_client{user="hello"} 2001047433 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 28690743529 (26.72 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 6617.3 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414900
telemt_connections_bad_total 15314
telemt_connections_current 2741
telemt_connections_me_current 2741
telemt_handshake_timeouts_total 5190
telemt_upstream_connect_attempt_total 1298
telemt_upstream_connect_success_total 1298
telemt_upstream_connect_attempts_per_request{bucket="1"} 1298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 16422
telemt_me_reconnect_success_total 914
telemt_me_reader_eof_total 857
telemt_me_idle_close_by_peer_total 857
telemt_me_route_drop_no_conn_total 278305
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358592
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 941
telemt_desync_full_logged_total 357
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 315
telemt_desync_frames_bucket_total{bucket="gt_10"} 432
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 868
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 853
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 358871
telemt_user_connections_current{user="hello"} 2741
telemt_user_octets_from_client{user="hello"} 5079446756 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 151261611932 (140.87 GB)
telemt_user_unique_ips_current{user="hello"} 841
telemt_user_unique_ips_recent_window{user="hello"} 404
```