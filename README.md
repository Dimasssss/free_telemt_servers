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

# Server Metrics 2026-03-18 10:52:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 7881.1 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288187
telemt_connections_bad_total 1819
telemt_handshake_timeouts_total 6729
telemt_upstream_connect_attempt_total 64540
telemt_upstream_connect_success_total 63612
telemt_upstream_connect_fail_total 928
telemt_upstream_connect_attempts_per_request{bucket="1"} 64540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 928
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 507882
telemt_me_reconnect_success_total 1239
telemt_me_reader_eof_total 1202
telemt_me_idle_close_by_peer_total 1200
telemt_me_route_drop_no_conn_total 166261
telemt_me_route_drop_channel_closed_total 54
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194528
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 867
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 590
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 323
telemt_desync_frames_bucket_total{bucket="gt_10"} 294
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1234
telemt_me_refill_failed_total 16516
telemt_me_writer_restored_same_endpoint_total 1134
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 253007
telemt_user_connections_current{user="hello"} 1490
telemt_user_octets_from_client{user="hello"} 3248101108 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 64406614597 (59.98 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 7912.3 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 857196
telemt_connections_bad_total 76406
telemt_handshake_timeouts_total 19282
telemt_upstream_connect_attempt_total 1346
telemt_upstream_connect_success_total 1334
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 917
telemt_me_reconnect_success_total 888
telemt_me_reader_eof_total 867
telemt_me_idle_close_by_peer_total 867
telemt_me_route_drop_no_conn_total 867072
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 721892
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2569
telemt_desync_full_logged_total 722
telemt_desync_suppressed_total 1847
telemt_desync_frames_bucket_total{bucket="1_2"} 520
telemt_desync_frames_bucket_total{bucket="3_10"} 1025
telemt_desync_frames_bucket_total{bucket="gt_10"} 1024
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 878
telemt_me_writer_restored_same_endpoint_total 887
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 721120
telemt_user_connections_current{user="hello"} 3689
telemt_user_octets_from_client{user="hello"} 11111436536 (10.35 GB)
telemt_user_octets_to_client{user="hello"} 197416540048 (183.86 GB)
telemt_user_unique_ips_current{user="hello"} 1134
telemt_user_unique_ips_recent_window{user="hello"} 533
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 7827.3 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 541400
telemt_connections_bad_total 37897
telemt_handshake_timeouts_total 13517
telemt_upstream_connect_attempt_total 9781
telemt_upstream_connect_success_total 9781
telemt_upstream_connect_attempts_per_request{bucket="1"} 9781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606822
telemt_me_reconnect_success_total 1146
telemt_me_reader_eof_total 1127
telemt_me_idle_close_by_peer_total 1126
telemt_me_route_drop_no_conn_total 271496
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408797
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1031
telemt_desync_full_logged_total 340
telemt_desync_suppressed_total 691
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 394
telemt_desync_frames_bucket_total{bucket="gt_10"} 382
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1144
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1111
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 416662
telemt_user_connections_current{user="hello"} 2905
telemt_user_octets_from_client{user="hello"} 4400916151 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 152786695204 (142.29 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 844
telemt_user_unique_ips_recent_window{user="hello"} 418
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 7857.6 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 989840
telemt_connections_bad_total 11831
telemt_handshake_timeouts_total 117585
telemt_upstream_connect_attempt_total 11913
telemt_upstream_connect_success_total 11779
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 11913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2818874
telemt_me_reconnect_success_total 1071
telemt_me_reader_eof_total 1279
telemt_me_idle_close_by_peer_total 1279
telemt_me_route_drop_no_conn_total 1746309
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 770646
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
telemt_desync_total 1295
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 909
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 455
telemt_me_writer_removed_unexpected_total 1316
telemt_me_refill_failed_total 99794
telemt_me_writer_restored_same_endpoint_total 976
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 789547
telemt_user_connections_current{user="hello"} 2776
telemt_user_octets_from_client{user="hello"} 5520253550 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 110473219805 (102.89 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 872
telemt_user_unique_ips_recent_window{user="hello"} 442
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 7752.6 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 534308
telemt_connections_bad_total 14628
telemt_handshake_timeouts_total 7686
telemt_upstream_connect_attempt_total 10936
telemt_upstream_connect_success_total 10935
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2982960
telemt_me_reconnect_success_total 1008
telemt_me_reader_eof_total 975
telemt_me_idle_close_by_peer_total 975
telemt_me_route_drop_no_conn_total 225224
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 450438
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1667
telemt_desync_full_logged_total 564
telemt_desync_suppressed_total 1103
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 762
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 967
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 893
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 458779
telemt_user_connections_current{user="hello"} 3669
telemt_user_octets_from_client{user="hello"} 7315557389 (6.81 GB)
telemt_user_octets_to_client{user="hello"} 185449687301 (172.71 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1070
telemt_user_unique_ips_recent_window{user="hello"} 512
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 7637.1 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164945
telemt_connections_bad_total 18157
telemt_handshake_timeouts_total 1066
telemt_upstream_connect_attempt_total 1395
telemt_upstream_connect_success_total 1395
telemt_upstream_connect_attempts_per_request{bucket="1"} 1395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 646
telemt_me_reconnect_attempts_total 963
telemt_me_reconnect_success_total 953
telemt_me_reader_eof_total 965
telemt_me_idle_close_by_peer_total 964
telemt_me_route_drop_no_conn_total 76835
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137982
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 357
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 956
telemt_me_writer_restored_same_endpoint_total 945
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 132480
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 1990653960 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 31093203556 (28.96 GB)
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 7708.4 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 388492
telemt_connections_bad_total 21366
telemt_handshake_timeouts_total 8814
telemt_upstream_connect_attempt_total 1405
telemt_upstream_connect_success_total 1386
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 962
telemt_me_reconnect_success_total 943
telemt_me_reader_eof_total 943
telemt_me_idle_close_by_peer_total 943
telemt_me_route_drop_no_conn_total 202642
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335254
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1187
telemt_desync_full_logged_total 422
telemt_desync_suppressed_total 765
telemt_desync_frames_bucket_total{bucket="1_2"} 233
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 525
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 939
telemt_me_writer_restored_same_endpoint_total 933
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 335052
telemt_user_connections_current{user="hello"} 2782
telemt_user_octets_from_client{user="hello"} 5770848280 (5.37 GB)
telemt_user_octets_to_client{user="hello"} 169513835104 (157.87 GB)
telemt_user_unique_ips_current{user="hello"} 806
telemt_user_unique_ips_recent_window{user="hello"} 361
```