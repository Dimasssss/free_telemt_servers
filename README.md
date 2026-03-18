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

# Server Metrics 2026-03-18 10:42:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 7270.0 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269504
telemt_connections_bad_total 1770
telemt_handshake_timeouts_total 6024
telemt_upstream_connect_attempt_total 64356
telemt_upstream_connect_success_total 63428
telemt_upstream_connect_fail_total 928
telemt_upstream_connect_attempts_per_request{bucket="1"} 64356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 928
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 507731
telemt_me_reconnect_success_total 1090
telemt_me_reader_eof_total 1051
telemt_me_idle_close_by_peer_total 1049
telemt_me_route_drop_no_conn_total 153457
telemt_me_route_drop_channel_closed_total 50
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177735
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 786
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 533
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 261
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1083
telemt_me_refill_failed_total 16516
telemt_me_writer_restored_same_endpoint_total 985
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 236221
telemt_user_connections_current{user="hello"} 1486
telemt_user_octets_from_client{user="hello"} 3029119048 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 60126112173 (56.00 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 7300.4 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 769007
telemt_connections_bad_total 73706
telemt_handshake_timeouts_total 14887
telemt_upstream_connect_attempt_total 1190
telemt_upstream_connect_success_total 1180
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 801
telemt_me_reconnect_success_total 775
telemt_me_reader_eof_total 751
telemt_me_idle_close_by_peer_total 751
telemt_me_route_drop_no_conn_total 694146
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 645003
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2435
telemt_desync_full_logged_total 686
telemt_desync_suppressed_total 1749
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 976
telemt_desync_frames_bucket_total{bucket="gt_10"} 986
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 762
telemt_me_writer_restored_same_endpoint_total 774
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 644199
telemt_user_connections_current{user="hello"} 4946
telemt_user_octets_from_client{user="hello"} 10520728892 (9.80 GB)
telemt_user_octets_to_client{user="hello"} 183749647284 (171.13 GB)
telemt_user_unique_ips_current{user="hello"} 1334
telemt_user_unique_ips_recent_window{user="hello"} 860
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 7215.6 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499720
telemt_connections_bad_total 33612
telemt_handshake_timeouts_total 12663
telemt_upstream_connect_attempt_total 9609
telemt_upstream_connect_success_total 9609
telemt_upstream_connect_attempts_per_request{bucket="1"} 9609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606695
telemt_me_reconnect_success_total 1022
telemt_me_reader_eof_total 1003
telemt_me_idle_close_by_peer_total 1002
telemt_me_route_drop_no_conn_total 259376
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375975
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 918
telemt_desync_full_logged_total 313
telemt_desync_suppressed_total 605
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 364
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1019
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 987
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 383852
telemt_user_connections_current{user="hello"} 2816
telemt_user_octets_from_client{user="hello"} 3916639691 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 136853524372 (127.45 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 828
telemt_user_unique_ips_recent_window{user="hello"} 444
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 7245.7 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 896213
telemt_connections_bad_total 10546
telemt_handshake_timeouts_total 106878
telemt_upstream_connect_attempt_total 11843
telemt_upstream_connect_success_total 11722
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 11843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2817475
telemt_me_reconnect_success_total 1050
telemt_me_reader_eof_total 1217
telemt_me_idle_close_by_peer_total 1217
telemt_me_route_drop_no_conn_total 1519072
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 693304
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
telemt_desync_total 1136
telemt_desync_full_logged_total 338
telemt_desync_suppressed_total 798
telemt_desync_frames_bucket_total{bucket="1_2"} 284
telemt_desync_frames_bucket_total{bucket="3_10"} 456
telemt_desync_frames_bucket_total{bucket="gt_10"} 396
telemt_me_writer_removed_unexpected_total 1251
telemt_me_refill_failed_total 99751
telemt_me_writer_restored_same_endpoint_total 955
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 712215
telemt_user_connections_current{user="hello"} 2957
telemt_user_octets_from_client{user="hello"} 5101796198 (4.75 GB)
telemt_user_octets_to_client{user="hello"} 102330395481 (95.30 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 870
telemt_user_unique_ips_recent_window{user="hello"} 724
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 7140.7 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491729
telemt_connections_bad_total 12955
telemt_handshake_timeouts_total 7199
telemt_upstream_connect_attempt_total 10839
telemt_upstream_connect_success_total 10838
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2982906
telemt_me_reconnect_success_total 955
telemt_me_reader_eof_total 916
telemt_me_idle_close_by_peer_total 916
telemt_me_route_drop_no_conn_total 206640
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 412464
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1517
telemt_desync_full_logged_total 521
telemt_desync_suppressed_total 996
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 595
telemt_desync_frames_bucket_total{bucket="gt_10"} 683
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 911
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 840
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 420818
telemt_user_connections_current{user="hello"} 3575
telemt_user_octets_from_client{user="hello"} 6695277625 (6.24 GB)
telemt_user_octets_to_client{user="hello"} 169101842905 (157.49 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1061
telemt_user_unique_ips_recent_window{user="hello"} 515
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 7025.8 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153101
telemt_connections_bad_total 17895
telemt_handshake_timeouts_total 965
telemt_upstream_connect_attempt_total 1255
telemt_upstream_connect_success_total 1255
telemt_upstream_connect_attempts_per_request{bucket="1"} 1255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 586
telemt_me_reconnect_attempts_total 870
telemt_me_reconnect_success_total 861
telemt_me_reader_eof_total 871
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 69437
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125051
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 311
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 862
telemt_me_writer_restored_same_endpoint_total 853
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 122195
telemt_user_connections_current{user="hello"} 941
telemt_user_octets_from_client{user="hello"} 1794448636 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 27129265464 (25.27 GB)
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 7096.4 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357890
telemt_connections_bad_total 20723
telemt_handshake_timeouts_total 7810
telemt_upstream_connect_attempt_total 1296
telemt_upstream_connect_success_total 1277
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 896
telemt_me_reconnect_success_total 877
telemt_me_reader_eof_total 871
telemt_me_idle_close_by_peer_total 871
telemt_me_route_drop_no_conn_total 192669
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307402
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1065
telemt_desync_full_logged_total 381
telemt_desync_suppressed_total 684
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 387
telemt_desync_frames_bucket_total{bucket="gt_10"} 466
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 871
telemt_me_writer_restored_same_endpoint_total 867
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 307211
telemt_user_connections_current{user="hello"} 2768
telemt_user_octets_from_client{user="hello"} 5257218048 (4.90 GB)
telemt_user_octets_to_client{user="hello"} 151596992384 (141.19 GB)
telemt_user_unique_ips_current{user="hello"} 785
telemt_user_unique_ips_recent_window{user="hello"} 375
```