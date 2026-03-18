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

# Server Metrics 2026-03-18 23:09:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 4852.5 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58312
telemt_connections_bad_total 6052
telemt_connections_current 708
telemt_connections_me_current 708
telemt_handshake_timeouts_total 654
telemt_upstream_connect_attempt_total 913
telemt_upstream_connect_success_total 901
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 624
telemt_me_reconnect_success_total 623
telemt_me_reader_eof_total 626
telemt_me_idle_close_by_peer_total 626
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 20829
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51523
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 254
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 616
telemt_me_writer_restored_same_endpoint_total 612
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 48766
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 524286652 (500.00 MB)
telemt_user_octets_to_client{user="hello"} 21123776872 (19.67 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 4855.7 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135353
telemt_connections_bad_total 5221
telemt_connections_current 1664
telemt_connections_me_current 1664
telemt_handshake_timeouts_total 1104
telemt_upstream_connect_attempt_total 871
telemt_upstream_connect_success_total 850
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 566
telemt_me_reconnect_success_total 565
telemt_me_reader_eof_total 573
telemt_me_idle_close_by_peer_total 573
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 45421
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121437
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 445
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 291
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 579
telemt_me_writer_restored_same_endpoint_total 554
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 121515
telemt_user_connections_current{user="hello"} 1664
telemt_user_octets_from_client{user="hello"} 9031692704 (8.41 GB)
telemt_user_octets_to_client{user="hello"} 48673492884 (45.33 GB)
telemt_user_unique_ips_current{user="hello"} 651
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 4852.9 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111822
telemt_connections_bad_total 16448
telemt_connections_current 1211
telemt_connections_me_current 1211
telemt_handshake_timeouts_total 3025
telemt_upstream_connect_attempt_total 947
telemt_upstream_connect_success_total 947
telemt_upstream_connect_attempts_per_request{bucket="1"} 947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 442
telemt_me_reconnect_attempts_total 664
telemt_me_reconnect_success_total 663
telemt_me_reader_eof_total 674
telemt_me_idle_close_by_peer_total 674
telemt_me_route_drop_no_conn_total 37989
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89167
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 368
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 153
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 669
telemt_me_writer_restored_same_endpoint_total 647
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 89169
telemt_user_connections_current{user="hello"} 1211
telemt_user_octets_from_client{user="hello"} 1285449176 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 57899487068 (53.92 GB)
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 4906.2 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126333
telemt_connections_bad_total 23254
telemt_connections_current 1124
telemt_connections_me_current 1124
telemt_handshake_timeouts_total 2881
telemt_upstream_connect_attempt_total 855
telemt_upstream_connect_success_total 855
telemt_upstream_connect_attempts_per_request{bucket="1"} 855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 575
telemt_me_reconnect_success_total 573
telemt_me_reader_eof_total 583
telemt_me_idle_close_by_peer_total 583
telemt_me_route_drop_no_conn_total 51346
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94489
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 213
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 583
telemt_me_writer_restored_same_endpoint_total 549
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 94418
telemt_user_connections_current{user="hello"} 1124
telemt_user_octets_from_client{user="hello"} 969100012 (924.21 MB)
telemt_user_octets_to_client{user="hello"} 33930677796 (31.60 GB)
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 4849.7 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120088
telemt_connections_bad_total 5443
telemt_connections_current 1301
telemt_connections_me_current 1301
telemt_handshake_timeouts_total 3732
telemt_upstream_connect_attempt_total 892
telemt_upstream_connect_success_total 886
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 602
telemt_me_reconnect_success_total 600
telemt_me_reader_eof_total 606
telemt_me_idle_close_by_peer_total 606
telemt_me_route_drop_no_conn_total 36074
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95126
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 439
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 260
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 601
telemt_me_writer_restored_same_endpoint_total 576
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 95090
telemt_user_connections_current{user="hello"} 1301
telemt_user_octets_from_client{user="hello"} 1242973568 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 57248983132 (53.32 GB)
telemt_user_unique_ips_current{user="hello"} 563
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 4861.1 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27622
telemt_connections_bad_total 5694
telemt_connections_current 387
telemt_connections_me_current 387
telemt_handshake_timeouts_total 84
telemt_upstream_connect_attempt_total 1474
telemt_upstream_connect_success_total 1425
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 1474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 610
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 1948
telemt_me_reconnect_success_total 1146
telemt_me_reader_eof_total 1141
telemt_me_idle_close_by_peer_total 1141
telemt_me_route_drop_no_conn_total 9161
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21209
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1144
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 1116
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 21209
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 280104800 (267.13 MB)
telemt_user_octets_to_client{user="hello"} 14594963592 (13.59 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 4851.9 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90644
telemt_connections_bad_total 12251
telemt_connections_current 1149
telemt_connections_me_current 1149
telemt_handshake_timeouts_total 2757
telemt_upstream_connect_attempt_total 889
telemt_upstream_connect_success_total 889
telemt_upstream_connect_attempts_per_request{bucket="1"} 889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 605
telemt_me_reconnect_success_total 604
telemt_me_reader_eof_total 616
telemt_me_idle_close_by_peer_total 616
telemt_me_route_drop_no_conn_total 26697
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73630
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 553
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 343
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 223
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 613
telemt_me_writer_restored_same_endpoint_total 589
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 73645
telemt_user_connections_current{user="hello"} 1149
telemt_user_octets_from_client{user="hello"} 792716424 (755.99 MB)
telemt_user_octets_to_client{user="hello"} 44358782956 (41.31 GB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 113
```