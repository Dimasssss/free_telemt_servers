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

# Server Metrics 2026-03-18 15:48:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1400.4 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48801
telemt_connections_bad_total 5106
telemt_handshake_timeouts_total 2674
telemt_upstream_connect_attempt_total 190
telemt_upstream_connect_success_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 95
telemt_me_reconnect_attempts_total 77
telemt_me_reconnect_success_total 77
telemt_me_reader_eof_total 58
telemt_me_idle_close_by_peer_total 58
telemt_me_route_drop_no_conn_total 16015
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37933
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 259
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 80
telemt_me_writer_restored_same_endpoint_total 66
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 37914
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 501586224 (478.35 MB)
telemt_user_octets_to_client{user="hello"} 9813258784 (9.14 GB)
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 6228.4 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672158
telemt_connections_bad_total 42340
telemt_connections_current 3537
telemt_connections_me_current 3537
telemt_handshake_timeouts_total 12572
telemt_upstream_connect_attempt_total 1060
telemt_upstream_connect_success_total 1054
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 723
telemt_me_reconnect_success_total 715
telemt_me_reader_eof_total 638
telemt_me_idle_close_by_peer_total 637
telemt_me_route_drop_no_conn_total 650067
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 584892
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1531
telemt_desync_full_logged_total 473
telemt_desync_suppressed_total 1058
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 609
telemt_desync_frames_bucket_total{bucket="gt_10"} 598
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 643
telemt_me_writer_restored_same_endpoint_total 713
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 584099
telemt_user_connections_current{user="hello"} 3537
telemt_user_octets_from_client{user="hello"} 5563263312 (5.18 GB)
telemt_user_octets_to_client{user="hello"} 159973016276 (148.99 GB)
telemt_user_unique_ips_current{user="hello"} 1139
telemt_user_unique_ips_recent_window{user="hello"} 483
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 6871.6 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635967
telemt_connections_bad_total 7798
telemt_connections_current 2345
telemt_connections_me_current 2345
telemt_handshake_timeouts_total 8730
telemt_upstream_connect_attempt_total 1123
telemt_upstream_connect_success_total 1114
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 735
telemt_me_reconnect_success_total 726
telemt_me_reader_eof_total 714
telemt_me_idle_close_by_peer_total 713
telemt_me_route_drop_no_conn_total 1077471
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 578322
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2124
telemt_desync_full_logged_total 524
telemt_desync_suppressed_total 1600
telemt_desync_frames_bucket_total{bucket="1_2"} 464
telemt_desync_frames_bucket_total{bucket="3_10"} 981
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 712
telemt_me_writer_restored_same_endpoint_total 715
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 578318
telemt_user_connections_current{user="hello"} 2345
telemt_user_octets_from_client{user="hello"} 4048184176 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 104077581620 (96.93 GB)
telemt_user_unique_ips_current{user="hello"} 778
telemt_user_unique_ips_recent_window{user="hello"} 345
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1386.1 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105601
telemt_connections_bad_total 17931
telemt_handshake_timeouts_total 1507
telemt_upstream_connect_attempt_total 240
telemt_upstream_connect_success_total 234
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 123
telemt_me_reconnect_success_total 121
telemt_me_reader_eof_total 90
telemt_me_idle_close_by_peer_total 90
telemt_me_route_drop_no_conn_total 35136
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79026
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 192
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 111
telemt_me_writer_restored_same_endpoint_total 95
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_user_connections_total{user="hello"} 78859
telemt_user_connections_current{user="hello"} 3004
telemt_user_octets_from_client{user="hello"} 1484589588 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 28211227388 (26.27 GB)
telemt_user_unique_ips_current{user="hello"} 970
telemt_user_unique_ips_recent_window{user="hello"} 417
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 6319.8 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126456
telemt_connections_bad_total 5682
telemt_connections_current 955
telemt_connections_me_current 955
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1169
telemt_upstream_connect_attempt_total 5154
telemt_upstream_connect_success_total 5147
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 5154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 330447
telemt_me_reconnect_success_total 990
telemt_me_reader_eof_total 920
telemt_me_idle_close_by_peer_total 920
telemt_me_route_drop_no_conn_total 71642
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109986
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 208
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 915
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 979
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 113737
telemt_user_connections_current{user="hello"} 955
telemt_user_octets_from_client{user="hello"} 1793667517 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 23554766169 (21.94 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 5390.4 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 346107
telemt_connections_bad_total 13927
telemt_connections_current 2594
telemt_connections_me_current 2594
telemt_handshake_timeouts_total 3669
telemt_upstream_connect_attempt_total 950
telemt_upstream_connect_success_total 950
telemt_upstream_connect_attempts_per_request{bucket="1"} 950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 435
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14948
telemt_me_reconnect_success_total 657
telemt_me_reader_eof_total 562
telemt_me_idle_close_by_peer_total 562
telemt_me_route_drop_no_conn_total 233837
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298664
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 756
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 332
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 571
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 596
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 298958
telemt_user_connections_current{user="hello"} 2594
telemt_user_octets_from_client{user="hello"} 4203260436 (3.91 GB)
telemt_user_octets_to_client{user="hello"} 121345602716 (113.01 GB)
telemt_user_unique_ips_current{user="hello"} 794
telemt_user_unique_ips_recent_window{user="hello"} 336
```