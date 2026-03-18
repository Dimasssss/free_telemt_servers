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

# Server Metrics 2026-03-18 10:26:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 6353.0 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236487
telemt_connections_bad_total 1714
telemt_handshake_timeouts_total 5159
telemt_upstream_connect_attempt_total 64171
telemt_upstream_connect_success_total 63247
telemt_upstream_connect_fail_total 924
telemt_upstream_connect_attempts_per_request{bucket="1"} 64171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 924
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 507592
telemt_me_reconnect_success_total 951
telemt_me_reader_eof_total 911
telemt_me_idle_close_by_peer_total 909
telemt_me_route_drop_no_conn_total 99497
telemt_me_route_drop_channel_closed_total 43
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147033
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 471
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 941
telemt_me_refill_failed_total 16516
telemt_me_writer_restored_same_endpoint_total 846
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 206650
telemt_user_connections_current{user="hello"} 1392
telemt_user_octets_from_client{user="hello"} 2514472860 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 52949329345 (49.31 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 468
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 6384.6 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 564372
telemt_connections_bad_total 65931
telemt_handshake_timeouts_total 13605
telemt_upstream_connect_attempt_total 1070
telemt_upstream_connect_success_total 1060
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 707
telemt_me_reconnect_success_total 683
telemt_me_reader_eof_total 656
telemt_me_idle_close_by_peer_total 656
telemt_me_route_drop_no_conn_total 229921
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 453558
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2217
telemt_desync_full_logged_total 616
telemt_desync_suppressed_total 1601
telemt_desync_frames_bucket_total{bucket="1_2"} 422
telemt_desync_frames_bucket_total{bucket="3_10"} 873
telemt_desync_frames_bucket_total{bucket="gt_10"} 922
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 670
telemt_me_writer_restored_same_endpoint_total 682
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 452696
telemt_user_connections_current{user="hello"} 3667
telemt_user_octets_from_client{user="hello"} 9791764212 (9.12 GB)
telemt_user_octets_to_client{user="hello"} 169514604936 (157.87 GB)
telemt_user_unique_ips_current{user="hello"} 1140
telemt_user_unique_ips_recent_window{user="hello"} 528
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 6299.2 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436808
telemt_connections_bad_total 26735
telemt_handshake_timeouts_total 11225
telemt_upstream_connect_attempt_total 9477
telemt_upstream_connect_success_total 9477
telemt_upstream_connect_attempts_per_request{bucket="1"} 9477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606606
telemt_me_reconnect_success_total 933
telemt_me_reader_eof_total 913
telemt_me_idle_close_by_peer_total 912
telemt_me_route_drop_no_conn_total 205736
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324405
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 494
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 929
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 898
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 332304
telemt_user_connections_current{user="hello"} 2598
telemt_user_octets_from_client{user="hello"} 3453912287 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 122921385168 (114.48 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 770
telemt_user_unique_ips_recent_window{user="hello"} 394
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 6329.6 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 804105
telemt_connections_bad_total 8681
telemt_handshake_timeouts_total 94593
telemt_upstream_connect_attempt_total 11748
telemt_upstream_connect_success_total 11628
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 11748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1106
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2816088
telemt_me_reconnect_success_total 1008
telemt_me_reader_eof_total 1135
telemt_me_idle_close_by_peer_total 1135
telemt_me_route_drop_no_conn_total 1407969
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 622613
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
telemt_desync_total 965
telemt_desync_full_logged_total 283
telemt_desync_suppressed_total 682
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 330
telemt_me_writer_removed_unexpected_total 1167
telemt_me_refill_failed_total 99709
telemt_me_writer_restored_same_endpoint_total 913
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 641539
telemt_user_connections_current{user="hello"} 2639
telemt_user_octets_from_client{user="hello"} 4646862966 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 86801463217 (80.84 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 828
telemt_user_unique_ips_recent_window{user="hello"} 474
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 6224.4 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429978
telemt_connections_bad_total 11786
telemt_handshake_timeouts_total 6568
telemt_upstream_connect_attempt_total 10715
telemt_upstream_connect_success_total 10714
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2982826
telemt_me_reconnect_success_total 875
telemt_me_reader_eof_total 829
telemt_me_idle_close_by_peer_total 829
telemt_me_route_drop_no_conn_total 183075
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357921
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1326
telemt_desync_full_logged_total 442
telemt_desync_suppressed_total 884
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 509
telemt_desync_frames_bucket_total{bucket="gt_10"} 601
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 829
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 760
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 366299
telemt_user_connections_current{user="hello"} 3342
telemt_user_octets_from_client{user="hello"} 5957581557 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 145829261865 (135.81 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1001
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 6109.2 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129633
telemt_connections_bad_total 16510
telemt_handshake_timeouts_total 761
telemt_upstream_connect_attempt_total 1128
telemt_upstream_connect_success_total 1128
telemt_upstream_connect_attempts_per_request{bucket="1"} 1128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 530
telemt_me_reconnect_attempts_total 786
telemt_me_reconnect_success_total 778
telemt_me_reader_eof_total 778
telemt_me_idle_close_by_peer_total 778
telemt_me_route_drop_no_conn_total 56294
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104130
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 244
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 774
telemt_me_writer_restored_same_endpoint_total 770
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 101725
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 1616570332 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 23075266020 (21.49 GB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 6180.3 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313934
telemt_connections_bad_total 19933
telemt_handshake_timeouts_total 5793
telemt_upstream_connect_attempt_total 1156
telemt_upstream_connect_success_total 1137
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 800
telemt_me_reconnect_success_total 787
telemt_me_reader_eof_total 779
telemt_me_idle_close_by_peer_total 779
telemt_me_route_drop_no_conn_total 172649
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267470
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 938
telemt_desync_full_logged_total 332
telemt_desync_suppressed_total 606
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 398
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 781
telemt_me_writer_restored_same_endpoint_total 777
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 267279
telemt_user_connections_current{user="hello"} 2355
telemt_user_octets_from_client{user="hello"} 4553983136 (4.24 GB)
telemt_user_octets_to_client{user="hello"} 130480642124 (121.52 GB)
telemt_user_unique_ips_current{user="hello"} 706
telemt_user_unique_ips_recent_window{user="hello"} 322
```