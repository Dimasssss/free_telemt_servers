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

# Server Metrics 2026-03-13 21:27:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 136431.3 (37h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 570226
telemt_connections_bad_total 16375
telemt_handshake_timeouts_total 12754
telemt_upstream_connect_attempt_total 34605
telemt_upstream_connect_success_total 34431
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 34605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5097
telemt_me_reconnect_attempts_total 31885
telemt_me_reconnect_success_total 27229
telemt_me_reader_eof_total 29068
telemt_me_idle_close_by_peer_total 29067
telemt_me_route_drop_no_conn_total 188089
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 490979
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1571
telemt_desync_full_logged_total 533
telemt_desync_suppressed_total 1038
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 582
telemt_desync_frames_bucket_total{bucket="gt_10"} 649
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 27681
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27213
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 490874
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 14741220498 (13.73 GB)
telemt_user_octets_to_client{user="hello"} 239504480788 (223.06 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 136324.4 (37h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289405
telemt_connections_bad_total 2136
telemt_handshake_timeouts_total 1902
telemt_upstream_connect_attempt_total 137938
telemt_upstream_connect_success_total 136939
telemt_upstream_connect_fail_total 999
telemt_upstream_connect_attempts_per_request{bucket="1"} 137938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2409
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 999
telemt_me_keepalive_timeout_total 3664
telemt_me_reconnect_attempts_total 143886
telemt_me_reconnect_success_total 26811
telemt_me_reader_eof_total 31206
telemt_me_idle_close_by_peer_total 31206
telemt_me_route_drop_no_conn_total 84970
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171467
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 30718
telemt_me_refill_failed_total 3653
telemt_me_writer_restored_same_endpoint_total 26794
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3907
telemt_user_connections_total{user="hello"} 274580
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 2841063215 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 83419259827 (77.69 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 136288.1 (37h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336982
telemt_connections_bad_total 2657
telemt_handshake_timeouts_total 26342
telemt_upstream_connect_attempt_total 36261
telemt_upstream_connect_success_total 36256
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 36261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2843
telemt_me_reconnect_attempts_total 30651
telemt_me_reconnect_success_total 29406
telemt_me_reader_eof_total 31544
telemt_me_idle_close_by_peer_total 31544
telemt_me_route_drop_no_conn_total 120238
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296113
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 29740
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29386
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 334
telemt_user_connections_total{user="hello"} 296015
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 12300100608 (11.46 GB)
telemt_user_octets_to_client{user="hello"} 123174613732 (114.72 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 136263.8 (37h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441960
telemt_connections_bad_total 15257
telemt_handshake_timeouts_total 4215
telemt_upstream_connect_attempt_total 63929
telemt_upstream_connect_success_total 53586
telemt_upstream_connect_fail_total 10343
telemt_upstream_connect_attempts_per_request{bucket="1"} 63929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 301
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10343
telemt_me_keepalive_timeout_total 4769
telemt_me_reconnect_attempts_total 127525
telemt_me_reconnect_success_total 27746
telemt_me_reader_eof_total 31642
telemt_me_idle_close_by_peer_total 31635
telemt_me_route_drop_no_conn_total 153678
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372668
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1572
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 1108
telemt_desync_frames_bucket_total{bucket="1_2"} 374
telemt_desync_frames_bucket_total{bucket="3_10"} 600
telemt_desync_frames_bucket_total{bucket="gt_10"} 598
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 31213
telemt_me_refill_failed_total 3112
telemt_me_writer_restored_same_endpoint_total 27736
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3467
telemt_user_connections_total{user="hello"} 391525
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 8847876971 (8.24 GB)
telemt_user_octets_to_client{user="hello"} 146786111112 (136.71 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 86435.3 (24h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147507
telemt_connections_bad_total 21466
telemt_handshake_timeouts_total 1524
telemt_upstream_connect_attempt_total 32353
telemt_upstream_connect_success_total 32045
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 32353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_keepalive_timeout_total 1289
telemt_me_reconnect_attempts_total 36243
telemt_me_reconnect_success_total 22848
telemt_me_reader_eof_total 24469
telemt_me_idle_close_by_peer_total 24469
telemt_me_route_drop_no_conn_total 45406
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115009
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 608
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 23482
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22830
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 119903
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 1382776069 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 55542530991 (51.73 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 136219.8 (37h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 828587
telemt_connections_bad_total 27124
telemt_handshake_timeouts_total 25070
telemt_upstream_connect_attempt_total 28063
telemt_upstream_connect_success_total 27915
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 28063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 3117
telemt_me_reconnect_attempts_total 25800
telemt_me_reconnect_success_total 21149
telemt_me_reader_eof_total 22684
telemt_me_idle_close_by_peer_total 22681
telemt_me_route_drop_no_conn_total 394006
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 775229
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 693
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 21577
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21142
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 748091
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 13045066700 (12.15 GB)
telemt_user_octets_to_client{user="hello"} 371069335268 (345.59 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 43
```