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

# Server Metrics 2026-03-19 14:25:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 1266.9 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100723
telemt_connections_bad_total 2
telemt_connections_current 102
telemt_connections_direct_current 102
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_demotions_total 273
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 82969
telemt_upstream_connect_attempt_total 3780
telemt_upstream_connect_success_total 3780
telemt_upstream_connect_attempts_per_request{bucket="1"} 3780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3778
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 34702817 (33.10 MB)
telemt_user_octets_to_client{user="hello"} 1147878064 (1.07 GB)
telemt_user_msgs_from_client{user="hello"} 37866
telemt_user_msgs_to_client{user="hello"} 92779
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 6087.6 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 655979
telemt_connections_bad_total 22429
telemt_connections_current 3596
telemt_connections_me_current 3596
telemt_handshake_timeouts_total 11985
telemt_upstream_connect_attempt_total 2460
telemt_upstream_connect_success_total 2445
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 5082
telemt_me_reconnect_success_total 882
telemt_me_reader_eof_total 972
telemt_me_idle_close_by_peer_total 972
telemt_me_route_drop_no_conn_total 554749
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 572906
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2039
telemt_desync_full_logged_total 640
telemt_desync_suppressed_total 1399
telemt_desync_frames_bucket_total{bucket="1_2"} 377
telemt_desync_frames_bucket_total{bucket="3_10"} 777
telemt_desync_frames_bucket_total{bucket="gt_10"} 885
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 996
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 827
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 573723
telemt_user_connections_current{user="hello"} 3596
telemt_user_octets_from_client{user="hello"} 7477693502 (6.96 GB)
telemt_user_octets_to_client{user="hello"} 145700889746 (135.69 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1261
telemt_user_unique_ips_recent_window{user="hello"} 541
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 6065.2 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 673936
telemt_connections_bad_total 68405
telemt_connections_current 2971
telemt_connections_me_current 2971
telemt_handshake_timeouts_total 6951
telemt_upstream_connect_attempt_total 953
telemt_upstream_connect_success_total 943
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 400
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1507
telemt_me_reconnect_success_total 606
telemt_me_reader_eof_total 553
telemt_me_idle_close_by_peer_total 552
telemt_me_route_drop_no_conn_total 652218
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 512043
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1775
telemt_desync_full_logged_total 472
telemt_desync_suppressed_total 1303
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 661
telemt_desync_frames_bucket_total{bucket="gt_10"} 627
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 564
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 605
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 509352
telemt_user_connections_current{user="hello"} 2971
telemt_user_octets_from_client{user="hello"} 4966599672 (4.63 GB)
telemt_user_octets_to_client{user="hello"} 132048744396 (122.98 GB)
telemt_user_unique_ips_current{user="hello"} 1070
telemt_user_unique_ips_recent_window{user="hello"} 454
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 6068.1 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 541989
telemt_connections_bad_total 40497
telemt_connections_current 2864
telemt_connections_me_current 2864
telemt_handshake_timeouts_total 8453
telemt_upstream_connect_attempt_total 9971
telemt_upstream_connect_success_total 9486
telemt_upstream_connect_fail_total 485
telemt_upstream_connect_attempts_per_request{bucket="1"} 9971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 485
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 888
telemt_me_reconnect_success_total 690
telemt_me_reader_eof_total 658
telemt_me_idle_close_by_peer_total 657
telemt_me_route_drop_no_conn_total 369191
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442884
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1962
telemt_desync_full_logged_total 631
telemt_desync_suppressed_total 1331
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 752
telemt_desync_frames_bucket_total{bucket="gt_10"} 814
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 76
telemt_me_writer_removed_unexpected_total 794
telemt_me_writer_restored_same_endpoint_total 686
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 450911
telemt_user_connections_current{user="hello"} 2864
telemt_user_octets_from_client{user="hello"} 7659822319 (7.13 GB)
telemt_user_octets_to_client{user="hello"} 96340427340 (89.72 GB)
telemt_user_msgs_from_client{user="hello"} 16739
telemt_user_msgs_to_client{user="hello"} 18599
telemt_user_unique_ips_current{user="hello"} 1016
telemt_user_unique_ips_recent_window{user="hello"} 459
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 59776.4 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4131005
telemt_connections_bad_total 773876
telemt_connections_current 3780
telemt_connections_me_current 3780
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 80507
telemt_upstream_connect_attempt_total 62536
telemt_upstream_connect_success_total 60052
telemt_upstream_connect_fail_total 2484
telemt_upstream_connect_attempts_per_request{bucket="1"} 62536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1021
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2484
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 73260
telemt_me_reconnect_success_total 7864
telemt_me_reader_eof_total 8276
telemt_me_idle_close_by_peer_total 8273
telemt_me_route_drop_no_conn_total 1972952
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2833906
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
telemt_desync_total 12245
telemt_desync_full_logged_total 3774
telemt_desync_suppressed_total 8471
telemt_desync_frames_bucket_total{bucket="1_2"} 2108
telemt_desync_frames_bucket_total{bucket="3_10"} 5252
telemt_desync_frames_bucket_total{bucket="gt_10"} 4885
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 8072
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 7840
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 2882574
telemt_user_connections_current{user="hello"} 3780
telemt_user_octets_from_client{user="hello"} 46184935427 (43.01 GB)
telemt_user_octets_to_client{user="hello"} 1028698755312 (958.05 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1195
telemt_user_unique_ips_recent_window{user="hello"} 603
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 6017.3 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143176
telemt_connections_bad_total 7162
telemt_connections_current 999
telemt_connections_me_current 999
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 4985
telemt_upstream_connect_attempt_total 3755
telemt_upstream_connect_success_total 3618
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 3755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2176
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 768
telemt_me_reconnect_success_total 745
telemt_me_reader_eof_total 707
telemt_me_idle_close_by_peer_total 707
telemt_me_route_drop_no_conn_total 101681
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121481
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 292
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 198
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 708
telemt_me_writer_restored_same_endpoint_total 736
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 124109
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 1788947700 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 29623992078 (27.59 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 6017.6 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413362
telemt_connections_bad_total 30587
telemt_connections_current 3003
telemt_connections_me_current 3003
telemt_handshake_timeouts_total 7738
telemt_upstream_connect_attempt_total 1003
telemt_upstream_connect_success_total 995
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 665
telemt_me_reconnect_success_total 652
telemt_me_reader_eof_total 664
telemt_me_idle_close_by_peer_total 664
telemt_me_route_drop_no_conn_total 144872
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360178
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1923
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 1348
telemt_desync_frames_bucket_total{bucket="1_2"} 346
telemt_desync_frames_bucket_total{bucket="3_10"} 619
telemt_desync_frames_bucket_total{bucket="gt_10"} 958
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 671
telemt_me_writer_restored_same_endpoint_total 635
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 359916
telemt_user_connections_current{user="hello"} 3003
telemt_user_octets_from_client{user="hello"} 4307973288 (4.01 GB)
telemt_user_octets_to_client{user="hello"} 149532919636 (139.26 GB)
telemt_user_unique_ips_current{user="hello"} 1001
telemt_user_unique_ips_recent_window{user="hello"} 423
```