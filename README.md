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

# Server Metrics 2026-03-18 14:05:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 19497.3 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 722104
telemt_connections_bad_total 36256
telemt_handshake_timeouts_total 19843
telemt_upstream_connect_attempt_total 66741
telemt_upstream_connect_success_total 65781
telemt_upstream_connect_fail_total 960
telemt_upstream_connect_attempts_per_request{bucket="1"} 66741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 960
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 514462
telemt_me_reconnect_success_total 2808
telemt_me_reader_eof_total 2981
telemt_me_idle_close_by_peer_total 2979
telemt_me_route_drop_no_conn_total 407773
telemt_me_route_drop_channel_closed_total 160
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559570
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2423
telemt_desync_full_logged_total 852
telemt_desync_suppressed_total 1571
telemt_desync_frames_bucket_total{bucket="1_2"} 669
telemt_desync_frames_bucket_total{bucket="3_10"} 838
telemt_desync_frames_bucket_total{bucket="gt_10"} 916
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2985
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2703
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 617726
telemt_user_connections_current{user="hello"} 1724
telemt_user_octets_from_client{user="hello"} 8506380192 (7.92 GB)
telemt_user_octets_to_client{user="hello"} 161402474597 (150.32 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 554
telemt_user_unique_ips_recent_window{user="hello"} 280
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 66.4 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20529
telemt_connections_bad_total 68
telemt_connections_current 3947
telemt_connections_me_current 3947
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 177
telemt_upstream_connect_success_total 176
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 109
telemt_me_reconnect_success_total 108
telemt_me_route_drop_no_conn_total 10216
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18959
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 106
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 18761
telemt_user_connections_current{user="hello"} 3947
telemt_user_octets_from_client{user="hello"} 60758324 (57.94 MB)
telemt_user_octets_to_client{user="hello"} 878973000 (838.25 MB)
telemt_user_unique_ips_current{user="hello"} 1114
telemt_user_unique_ips_recent_window{user="hello"} 1287
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 19443.4 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1409507
telemt_connections_bad_total 106972
telemt_handshake_timeouts_total 31192
telemt_upstream_connect_attempt_total 11969
telemt_upstream_connect_success_total 11969
telemt_upstream_connect_attempts_per_request{bucket="1"} 11969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3094
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 449
telemt_me_reconnect_attempts_total 612335
telemt_me_reconnect_success_total 2730
telemt_me_reader_eof_total 2891
telemt_me_idle_close_by_peer_total 2890
telemt_me_route_drop_no_conn_total 689121
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1106480
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3468
telemt_desync_full_logged_total 1136
telemt_desync_suppressed_total 2332
telemt_desync_frames_bucket_total{bucket="1_2"} 960
telemt_desync_frames_bucket_total{bucket="3_10"} 1249
telemt_desync_frames_bucket_total{bucket="gt_10"} 1259
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2871
telemt_me_refill_failed_total 19794
telemt_me_writer_restored_same_endpoint_total 2695
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 1113954
telemt_user_connections_current{user="hello"} 3234
telemt_user_octets_from_client{user="hello"} 14505487451 (13.51 GB)
telemt_user_octets_to_client{user="hello"} 451855536812 (420.82 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1021
telemt_user_unique_ips_recent_window{user="hello"} 504
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 708.3 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83916
telemt_connections_bad_total 216
telemt_connections_current 3051
telemt_connections_me_current 3051
telemt_handshake_timeouts_total 1316
telemt_upstream_connect_attempt_total 151
telemt_upstream_connect_success_total 150
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 81
telemt_me_reconnect_success_total 80
telemt_me_reader_eof_total 27
telemt_me_idle_close_by_peer_total 27
telemt_me_route_drop_no_conn_total 159166
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74648
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_me_writer_removed_unexpected_total 49
telemt_me_writer_restored_same_endpoint_total 69
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 74638
telemt_user_connections_current{user="hello"} 3051
telemt_user_octets_from_client{user="hello"} 405828784 (387.03 MB)
telemt_user_octets_to_client{user="hello"} 7770752856 (7.24 GB)
telemt_user_unique_ips_current{user="hello"} 837
telemt_user_unique_ips_recent_window{user="hello"} 825
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 19368.1 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1546708
telemt_connections_bad_total 108395
telemt_handshake_timeouts_total 25549
telemt_upstream_connect_attempt_total 14951
telemt_upstream_connect_success_total 14923
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 14951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1861
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986701
telemt_me_reconnect_success_total 2264
telemt_me_reader_eof_total 2371
telemt_me_idle_close_by_peer_total 2371
telemt_me_route_drop_no_conn_total 1502193
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1294582
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3782
telemt_desync_full_logged_total 1298
telemt_desync_suppressed_total 2484
telemt_desync_frames_bucket_total{bucket="1_2"} 586
telemt_desync_frames_bucket_total{bucket="3_10"} 1463
telemt_desync_frames_bucket_total{bucket="gt_10"} 1733
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2330
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2149
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 1296454
telemt_user_connections_current{user="hello"} 3558
telemt_user_octets_from_client{user="hello"} 20043507831 (18.67 GB)
telemt_user_octets_to_client{user="hello"} 448349752133 (417.56 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 1134
telemt_user_unique_ips_recent_window{user="hello"} 859
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 156.8 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7637
telemt_connections_bad_total 89
telemt_connections_current 701
telemt_connections_me_current 701
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 4124
telemt_upstream_connect_success_total 4122
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 329620
telemt_me_reconnect_success_total 234
telemt_me_reader_eof_total 114
telemt_me_idle_close_by_peer_total 114
telemt_me_route_drop_no_conn_total 910
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3175
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 6
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 129
telemt_me_refill_failed_total 10446
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 6962
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 71235581 (67.94 MB)
telemt_user_octets_to_client{user="hello"} 549998049 (524.52 MB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 293
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 19324.3 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1252009
telemt_connections_bad_total 144556
telemt_handshake_timeouts_total 24585
telemt_upstream_connect_attempt_total 3564
telemt_upstream_connect_success_total 3531
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 3564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1551
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 6262
telemt_me_reconnect_success_total 2472
telemt_me_reader_eof_total 2644
telemt_me_idle_close_by_peer_total 2644
telemt_me_route_drop_no_conn_total 747684
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 987014
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3308
telemt_desync_full_logged_total 1100
telemt_desync_suppressed_total 2208
telemt_desync_frames_bucket_total{bucket="1_2"} 610
telemt_desync_frames_bucket_total{bucket="3_10"} 1121
telemt_desync_frames_bucket_total{bucket="gt_10"} 1577
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2612
telemt_me_refill_failed_total 117
telemt_me_writer_restored_same_endpoint_total 2462
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 986340
telemt_user_connections_current{user="hello"} 3139
telemt_user_octets_from_client{user="hello"} 19589550192 (18.24 GB)
telemt_user_octets_to_client{user="hello"} 444376258128 (413.86 GB)
telemt_user_unique_ips_current{user="hello"} 965
telemt_user_unique_ips_recent_window{user="hello"} 567
```