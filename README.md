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

# Server Metrics 2026-03-18 17:15:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 6627.0 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202306
telemt_connections_bad_total 13851
telemt_handshake_timeouts_total 5642
telemt_upstream_connect_attempt_total 1089
telemt_upstream_connect_success_total 1089
telemt_upstream_connect_attempts_per_request{bucket="1"} 1089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 718
telemt_me_reconnect_success_total 716
telemt_me_reader_eof_total 732
telemt_me_idle_close_by_peer_total 732
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 98349
telemt_me_route_drop_channel_closed_total 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169303
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 935
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 653
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 305
telemt_desync_frames_bucket_total{bucket="gt_10"} 402
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 734
telemt_me_writer_restored_same_endpoint_total 703
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 169224
telemt_user_connections_current{user="hello"} 1391
telemt_user_octets_from_client{user="hello"} 2317970692 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 57292876680 (53.36 GB)
telemt_user_unique_ips_current{user="hello"} 481
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 11455.4 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1140173
telemt_connections_bad_total 72449
telemt_connections_current 3720
telemt_connections_me_current 3720
telemt_handshake_timeouts_total 16758
telemt_upstream_connect_attempt_total 2039
telemt_upstream_connect_success_total 2029
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1438
telemt_me_reconnect_success_total 1428
telemt_me_reader_eof_total 1385
telemt_me_idle_close_by_peer_total 1384
telemt_me_route_drop_no_conn_total 1059444
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 995292
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2893
telemt_desync_full_logged_total 934
telemt_desync_suppressed_total 1959
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 1149
telemt_desync_frames_bucket_total{bucket="gt_10"} 1177
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1362
telemt_me_writer_restored_same_endpoint_total 1426
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 994437
telemt_user_connections_current{user="hello"} 3720
telemt_user_octets_from_client{user="hello"} 12888428148 (12.00 GB)
telemt_user_octets_to_client{user="hello"} 298602795012 (278.10 GB)
telemt_user_unique_ips_current{user="hello"} 1168
telemt_user_unique_ips_recent_window{user="hello"} 520
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 11383.7 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 804116
telemt_connections_bad_total 58293
telemt_connections_current 3122
telemt_connections_me_current 3122
telemt_handshake_timeouts_total 17426
telemt_upstream_connect_attempt_total 1598
telemt_upstream_connect_success_total 1590
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 998
telemt_me_reconnect_success_total 988
telemt_me_reader_eof_total 1044
telemt_me_idle_close_by_peer_total 1044
telemt_me_route_drop_no_conn_total 385215
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 674019
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2704
telemt_desync_full_logged_total 814
telemt_desync_suppressed_total 1890
telemt_desync_frames_bucket_total{bucket="1_2"} 617
telemt_desync_frames_bucket_total{bucket="3_10"} 1012
telemt_desync_frames_bucket_total{bucket="gt_10"} 1075
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1022
telemt_me_writer_restored_same_endpoint_total 971
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 673663
telemt_user_connections_current{user="hello"} 3122
telemt_user_octets_from_client{user="hello"} 13011760212 (12.12 GB)
telemt_user_octets_to_client{user="hello"} 284833511188 (265.27 GB)
telemt_user_unique_ips_current{user="hello"} 1008
telemt_user_unique_ips_recent_window{user="hello"} 444
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 12098.1 (3h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1171370
telemt_connections_bad_total 25927
telemt_connections_current 2870
telemt_connections_me_current 2870
telemt_handshake_timeouts_total 14455
telemt_upstream_connect_attempt_total 1909
telemt_upstream_connect_success_total 1896
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1257
telemt_me_reconnect_success_total 1242
telemt_me_reader_eof_total 1264
telemt_me_idle_close_by_peer_total 1263
telemt_me_route_drop_no_conn_total 1931014
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1050083
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3900
telemt_desync_full_logged_total 1002
telemt_desync_suppressed_total 2898
telemt_desync_frames_bucket_total{bucket="1_2"} 913
telemt_desync_frames_bucket_total{bucket="3_10"} 1761
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1237
telemt_me_writer_restored_same_endpoint_total 1231
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 1050001
telemt_user_connections_current{user="hello"} 2870
telemt_user_octets_from_client{user="hello"} 8913263700 (8.30 GB)
telemt_user_octets_to_client{user="hello"} 183308702824 (170.72 GB)
telemt_user_unique_ips_current{user="hello"} 881
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 6613.0 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504597
telemt_connections_bad_total 90378
telemt_handshake_timeouts_total 4716
telemt_upstream_connect_attempt_total 1179
telemt_upstream_connect_success_total 1143
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 1179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1766
telemt_me_reconnect_success_total 766
telemt_me_reader_eof_total 794
telemt_me_idle_close_by_peer_total 794
telemt_me_route_drop_no_conn_total 211697
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 371150
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1375
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 906
telemt_desync_frames_bucket_total{bucket="1_2"} 233
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 698
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 803
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 740
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 370703
telemt_user_connections_current{user="hello"} 3207
telemt_user_octets_from_client{user="hello"} 5873868912 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 153652910752 (143.10 GB)
telemt_user_unique_ips_current{user="hello"} 1046
telemt_user_unique_ips_recent_window{user="hello"} 431
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 11549.0 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209156
telemt_connections_bad_total 7682
telemt_connections_current 796
telemt_connections_me_current 796
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2120
telemt_upstream_connect_attempt_total 6154
telemt_upstream_connect_success_total 6142
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 6154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 331177
telemt_me_reconnect_success_total 1713
telemt_me_reader_eof_total 1682
telemt_me_idle_close_by_peer_total 1682
telemt_me_route_drop_no_conn_total 117025
telemt_me_route_drop_channel_closed_total 50
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185437
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 388
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 249
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 164
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1649
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1702
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 189160
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 2706231129 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 39938076841 (37.20 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 10617.3 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 653027
telemt_connections_bad_total 44201
telemt_connections_current 2807
telemt_connections_me_current 2807
telemt_handshake_timeouts_total 13021
telemt_upstream_connect_attempt_total 1901
telemt_upstream_connect_success_total 1900
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 844
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16852
telemt_me_reconnect_success_total 1339
telemt_me_reader_eof_total 1313
telemt_me_idle_close_by_peer_total 1313
telemt_me_route_drop_no_conn_total 381972
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547371
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2069
telemt_desync_full_logged_total 715
telemt_desync_suppressed_total 1354
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 742
telemt_desync_frames_bucket_total{bucket="gt_10"} 829
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1300
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1278
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 546414
telemt_user_connections_current{user="hello"} 2807
telemt_user_octets_from_client{user="hello"} 10198483952 (9.50 GB)
telemt_user_octets_to_client{user="hello"} 262013600440 (244.02 GB)
telemt_user_unique_ips_current{user="hello"} 861
telemt_user_unique_ips_recent_window{user="hello"} 358
```