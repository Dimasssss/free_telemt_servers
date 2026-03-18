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

# Server Metrics 2026-03-18 10:37:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 6964.1 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256928
telemt_connections_bad_total 1748
telemt_handshake_timeouts_total 5778
telemt_upstream_connect_attempt_total 64322
telemt_upstream_connect_success_total 63394
telemt_upstream_connect_fail_total 928
telemt_upstream_connect_attempts_per_request{bucket="1"} 64322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 928
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 507710
telemt_me_reconnect_success_total 1069
telemt_me_reader_eof_total 1027
telemt_me_idle_close_by_peer_total 1025
telemt_me_route_drop_no_conn_total 126182
telemt_me_route_drop_channel_closed_total 48
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165936
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 741
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 500
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 276
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1059
telemt_me_refill_failed_total 16516
telemt_me_writer_restored_same_endpoint_total 964
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 224426
telemt_user_connections_current{user="hello"} 1495
telemt_user_octets_from_client{user="hello"} 2739444816 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 58403880069 (54.39 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 6994.7 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 670316
telemt_connections_bad_total 71982
telemt_handshake_timeouts_total 14361
telemt_upstream_connect_attempt_total 1158
telemt_upstream_connect_success_total 1148
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 780
telemt_me_reconnect_success_total 754
telemt_me_reader_eof_total 730
telemt_me_idle_close_by_peer_total 730
telemt_me_route_drop_no_conn_total 437965
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 550640
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2355
telemt_desync_full_logged_total 664
telemt_desync_suppressed_total 1691
telemt_desync_frames_bucket_total{bucket="1_2"} 454
telemt_desync_frames_bucket_total{bucket="3_10"} 934
telemt_desync_frames_bucket_total{bucket="gt_10"} 967
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 741
telemt_me_writer_restored_same_endpoint_total 753
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 549825
telemt_user_connections_current{user="hello"} 4338
telemt_user_octets_from_client{user="hello"} 10294444332 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 181931096048 (169.44 GB)
telemt_user_unique_ips_current{user="hello"} 1248
telemt_user_unique_ips_recent_window{user="hello"} 781
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 6910.0 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478930
telemt_connections_bad_total 31383
telemt_handshake_timeouts_total 12168
telemt_upstream_connect_attempt_total 9593
telemt_upstream_connect_success_total 9593
telemt_upstream_connect_attempts_per_request{bucket="1"} 9593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606679
telemt_me_reconnect_success_total 1006
telemt_me_reader_eof_total 988
telemt_me_idle_close_by_peer_total 987
telemt_me_route_drop_no_conn_total 248917
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 359102
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 876
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 579
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1003
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 971
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 366987
telemt_user_connections_current{user="hello"} 2963
telemt_user_octets_from_client{user="hello"} 3791569103 (3.53 GB)
telemt_user_octets_to_client{user="hello"} 132010632304 (122.94 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 850
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 6939.9 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 856229
telemt_connections_bad_total 10202
telemt_handshake_timeouts_total 103873
telemt_upstream_connect_attempt_total 11820
telemt_upstream_connect_success_total 11699
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 11820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2817462
telemt_me_reconnect_success_total 1037
telemt_me_reader_eof_total 1204
telemt_me_idle_close_by_peer_total 1204
telemt_me_route_drop_no_conn_total 1443709
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 658655
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1100
telemt_desync_full_logged_total 326
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 440
telemt_desync_frames_bucket_total{bucket="gt_10"} 388
telemt_me_writer_removed_unexpected_total 1238
telemt_me_refill_failed_total 99751
telemt_me_writer_restored_same_endpoint_total 942
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 677570
telemt_user_connections_current{user="hello"} 2683
telemt_user_octets_from_client{user="hello"} 4924178422 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 97144661337 (90.47 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 818
telemt_user_unique_ips_recent_window{user="hello"} 453
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 6834.8 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469684
telemt_connections_bad_total 12576
telemt_handshake_timeouts_total 6901
telemt_upstream_connect_attempt_total 10825
telemt_upstream_connect_success_total 10824
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2982892
telemt_me_reconnect_success_total 941
telemt_me_reader_eof_total 900
telemt_me_idle_close_by_peer_total 900
telemt_me_route_drop_no_conn_total 197572
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393335
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1450
telemt_desync_full_logged_total 494
telemt_desync_suppressed_total 956
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 556
telemt_desync_frames_bucket_total{bucket="gt_10"} 666
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 895
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 826
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 401696
telemt_user_connections_current{user="hello"} 3325
telemt_user_octets_from_client{user="hello"} 6479583325 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 160915922481 (149.86 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1017
telemt_user_unique_ips_recent_window{user="hello"} 490
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 6720.0 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142985
telemt_connections_bad_total 17088
telemt_handshake_timeouts_total 906
telemt_upstream_connect_attempt_total 1236
telemt_upstream_connect_success_total 1236
telemt_upstream_connect_attempts_per_request{bucket="1"} 1236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 580
telemt_me_reconnect_attempts_total 851
telemt_me_reconnect_success_total 842
telemt_me_reader_eof_total 850
telemt_me_idle_close_by_peer_total 850
telemt_me_route_drop_no_conn_total 64028
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116277
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 291
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 184
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 841
telemt_me_writer_restored_same_endpoint_total 834
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 113422
telemt_user_connections_current{user="hello"} 948
telemt_user_octets_from_client{user="hello"} 1678378252 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 25440425236 (23.69 GB)
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 6790.9 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343009
telemt_connections_bad_total 20408
telemt_handshake_timeouts_total 7200
telemt_upstream_connect_attempt_total 1269
telemt_upstream_connect_success_total 1250
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 869
telemt_me_reconnect_success_total 855
telemt_me_reader_eof_total 850
telemt_me_idle_close_by_peer_total 850
telemt_me_route_drop_no_conn_total 187073
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293845
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1028
telemt_desync_full_logged_total 369
telemt_desync_suppressed_total 659
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 378
telemt_desync_frames_bucket_total{bucket="gt_10"} 440
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 849
telemt_me_writer_restored_same_endpoint_total 845
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 293651
telemt_user_connections_current{user="hello"} 2423
telemt_user_octets_from_client{user="hello"} 5012134340 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 144065567740 (134.17 GB)
telemt_user_unique_ips_current{user="hello"} 714
telemt_user_unique_ips_recent_window{user="hello"} 446
```