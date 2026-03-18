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

# Server Metrics 2026-03-18 17:05:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 6009.2 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186157
telemt_connections_bad_total 13188
telemt_handshake_timeouts_total 5505
telemt_upstream_connect_attempt_total 945
telemt_upstream_connect_success_total 945
telemt_upstream_connect_attempts_per_request{bucket="1"} 945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 617
telemt_me_reconnect_success_total 615
telemt_me_reader_eof_total 618
telemt_me_idle_close_by_peer_total 618
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 92988
telemt_me_route_drop_channel_closed_total 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154558
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 856
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 602
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 366
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 632
telemt_me_writer_restored_same_endpoint_total 602
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 154488
telemt_user_connections_current{user="hello"} 1586
telemt_user_octets_from_client{user="hello"} 2098384916 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 52532537592 (48.92 GB)
telemt_user_unique_ips_current{user="hello"} 517
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 10837.6 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1093699
telemt_connections_bad_total 70137
telemt_connections_current 3935
telemt_connections_me_current 3935
telemt_handshake_timeouts_total 16476
telemt_upstream_connect_attempt_total 1928
telemt_upstream_connect_success_total 1918
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 861
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1365
telemt_me_reconnect_success_total 1354
telemt_me_reader_eof_total 1308
telemt_me_idle_close_by_peer_total 1307
telemt_me_route_drop_no_conn_total 1037506
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 953771
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2723
telemt_desync_full_logged_total 869
telemt_desync_suppressed_total 1854
telemt_desync_frames_bucket_total{bucket="1_2"} 537
telemt_desync_frames_bucket_total{bucket="3_10"} 1097
telemt_desync_frames_bucket_total{bucket="gt_10"} 1089
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1289
telemt_me_writer_restored_same_endpoint_total 1352
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 952916
telemt_user_connections_current{user="hello"} 3935
telemt_user_octets_from_client{user="hello"} 12334066724 (11.49 GB)
telemt_user_octets_to_client{user="hello"} 280544134016 (261.28 GB)
telemt_user_unique_ips_current{user="hello"} 1210
telemt_user_unique_ips_recent_window{user="hello"} 593
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 10765.7 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 757076
telemt_connections_bad_total 53660
telemt_connections_current 3342
telemt_connections_me_current 3342
telemt_handshake_timeouts_total 16337
telemt_upstream_connect_attempt_total 1488
telemt_upstream_connect_success_total 1481
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 932
telemt_me_reconnect_success_total 922
telemt_me_reader_eof_total 970
telemt_me_idle_close_by_peer_total 970
telemt_me_route_drop_no_conn_total 367574
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636597
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2579
telemt_desync_full_logged_total 758
telemt_desync_suppressed_total 1821
telemt_desync_frames_bucket_total{bucket="1_2"} 589
telemt_desync_frames_bucket_total{bucket="3_10"} 960
telemt_desync_frames_bucket_total{bucket="gt_10"} 1030
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 954
telemt_me_writer_restored_same_endpoint_total 905
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 636246
telemt_user_connections_current{user="hello"} 3342
telemt_user_octets_from_client{user="hello"} 11971608928 (11.15 GB)
telemt_user_octets_to_client{user="hello"} 266539454560 (248.23 GB)
telemt_user_unique_ips_current{user="hello"} 1012
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 11480.5 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1101204
telemt_connections_bad_total 25128
telemt_connections_current 3171
telemt_connections_me_current 3171
telemt_handshake_timeouts_total 14133
telemt_upstream_connect_attempt_total 1809
telemt_upstream_connect_success_total 1797
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1200
telemt_me_reconnect_success_total 1189
telemt_me_reader_eof_total 1207
telemt_me_idle_close_by_peer_total 1206
telemt_me_route_drop_no_conn_total 1803481
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 987148
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3663
telemt_desync_full_logged_total 928
telemt_desync_suppressed_total 2735
telemt_desync_frames_bucket_total{bucket="1_2"} 857
telemt_desync_frames_bucket_total{bucket="3_10"} 1674
telemt_desync_frames_bucket_total{bucket="gt_10"} 1132
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1183
telemt_me_writer_restored_same_endpoint_total 1178
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 987072
telemt_user_connections_current{user="hello"} 3171
telemt_user_octets_from_client{user="hello"} 8561570488 (7.97 GB)
telemt_user_octets_to_client{user="hello"} 173755264740 (161.82 GB)
telemt_user_unique_ips_current{user="hello"} 901
telemt_user_unique_ips_recent_window{user="hello"} 454
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5995.2 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467585
telemt_connections_bad_total 88376
telemt_handshake_timeouts_total 4367
telemt_upstream_connect_attempt_total 1045
telemt_upstream_connect_success_total 1014
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 1045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1680
telemt_me_reconnect_success_total 680
telemt_me_reader_eof_total 708
telemt_me_idle_close_by_peer_total 708
telemt_me_route_drop_no_conn_total 197855
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339315
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1208
telemt_desync_full_logged_total 423
telemt_desync_suppressed_total 785
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 390
telemt_desync_frames_bucket_total{bucket="gt_10"} 626
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 717
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 654
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 338890
telemt_user_connections_current{user="hello"} 3583
telemt_user_octets_from_client{user="hello"} 5052992108 (4.71 GB)
telemt_user_octets_to_client{user="hello"} 137518569792 (128.07 GB)
telemt_user_unique_ips_current{user="hello"} 1094
telemt_user_unique_ips_recent_window{user="hello"} 498
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 10931.7 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200654
telemt_connections_bad_total 7679
telemt_connections_current 860
telemt_connections_me_current 860
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1939
telemt_upstream_connect_attempt_total 6080
telemt_upstream_connect_success_total 6068
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 6080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 331103
telemt_me_reconnect_success_total 1640
telemt_me_reader_eof_total 1604
telemt_me_idle_close_by_peer_total 1604
telemt_me_route_drop_no_conn_total 112529
telemt_me_route_drop_channel_closed_total 43
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177483
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 365
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1575
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1629
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 181206
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 2648972281 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 38199371213 (35.58 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 9999.7 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600606
telemt_connections_bad_total 24724
telemt_connections_current 2782
telemt_connections_me_current 2782
telemt_handshake_timeouts_total 12389
telemt_upstream_connect_attempt_total 1827
telemt_upstream_connect_success_total 1826
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16778
telemt_me_reconnect_success_total 1266
telemt_me_reader_eof_total 1233
telemt_me_idle_close_by_peer_total 1233
telemt_me_route_drop_no_conn_total 371809
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517887
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1882
telemt_desync_full_logged_total 658
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 454
telemt_desync_frames_bucket_total{bucket="3_10"} 680
telemt_desync_frames_bucket_total{bucket="gt_10"} 748
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1225
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1205
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 516943
telemt_user_connections_current{user="hello"} 2782
telemt_user_octets_from_client{user="hello"} 9052990588 (8.43 GB)
telemt_user_octets_to_client{user="hello"} 242987477608 (226.30 GB)
telemt_user_unique_ips_current{user="hello"} 870
telemt_user_unique_ips_recent_window{user="hello"} 401
```