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

# Server Metrics 2026-03-19 10:44:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 46568.4 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1069128
telemt_connections_bad_total 92149
telemt_connections_current 1464
telemt_connections_me_current 1464
telemt_handshake_timeouts_total 37744
telemt_upstream_connect_attempt_total 8847
telemt_upstream_connect_success_total 8692
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 8847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 7522
telemt_me_reconnect_success_total 6357
telemt_me_reader_eof_total 6718
telemt_me_idle_close_by_peer_total 6715
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 410330
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 827804
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4687
telemt_desync_full_logged_total 1440
telemt_desync_suppressed_total 3247
telemt_desync_frames_bucket_total{bucket="1_2"} 1546
telemt_desync_frames_bucket_total{bucket="3_10"} 1716
telemt_desync_frames_bucket_total{bucket="gt_10"} 1425
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6484
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 6336
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 821849
telemt_user_connections_current{user="hello"} 1464
telemt_user_octets_from_client{user="hello"} 12455067764 (11.60 GB)
telemt_user_octets_to_client{user="hello"} 255195407272 (237.67 GB)
telemt_user_unique_ips_current{user="hello"} 531
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 46572.7 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2675038
telemt_connections_bad_total 163987
telemt_connections_current 3947
telemt_connections_me_current 3947
telemt_handshake_timeouts_total 55479
telemt_upstream_connect_attempt_total 8904
telemt_upstream_connect_success_total 8740
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 8904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 9798
telemt_me_reconnect_success_total 6385
telemt_me_reader_eof_total 6808
telemt_me_idle_close_by_peer_total 6807
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1409963
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2231421
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9810
telemt_desync_full_logged_total 3266
telemt_desync_suppressed_total 6544
telemt_desync_frames_bucket_total{bucket="1_2"} 1848
telemt_desync_frames_bucket_total{bucket="3_10"} 3850
telemt_desync_frames_bucket_total{bucket="gt_10"} 4112
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6607
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 6363
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 2231090
telemt_user_connections_current{user="hello"} 3947
telemt_user_octets_from_client{user="hello"} 33190978448 (30.91 GB)
telemt_user_octets_to_client{user="hello"} 770157320156 (717.26 GB)
telemt_user_unique_ips_current{user="hello"} 1418
telemt_user_unique_ips_recent_window{user="hello"} 695
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 46570.0 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2256407
telemt_connections_bad_total 264945
telemt_connections_current 3023
telemt_connections_me_current 3023
telemt_handshake_timeouts_total 49488
telemt_upstream_connect_attempt_total 8289
telemt_upstream_connect_success_total 8289
telemt_upstream_connect_attempts_per_request{bucket="1"} 8289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3923
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5971
telemt_me_reconnect_success_total 5932
telemt_me_reader_eof_total 6274
telemt_me_idle_close_by_peer_total 6274
telemt_me_route_drop_no_conn_total 1393215
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1771817
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7590
telemt_desync_full_logged_total 2418
telemt_desync_suppressed_total 5172
telemt_desync_frames_bucket_total{bucket="1_2"} 1685
telemt_desync_frames_bucket_total{bucket="3_10"} 2804
telemt_desync_frames_bucket_total{bucket="gt_10"} 3101
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6037
telemt_me_writer_restored_same_endpoint_total 5916
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 1770155
telemt_user_connections_current{user="hello"} 3023
telemt_user_octets_from_client{user="hello"} 25141416228 (23.41 GB)
telemt_user_octets_to_client{user="hello"} 763191151820 (710.78 GB)
telemt_user_unique_ips_current{user="hello"} 1058
telemt_user_unique_ips_recent_window{user="hello"} 493
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 46623.1 (12h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2233391
telemt_connections_bad_total 121411
telemt_connections_current 2912
telemt_connections_me_current 2912
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 59080
telemt_upstream_connect_attempt_total 16607
telemt_upstream_connect_success_total 16448
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 16607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9263
telemt_me_reconnect_success_total 5934
telemt_me_reader_eof_total 6304
telemt_me_idle_close_by_peer_total 6303
telemt_me_route_drop_no_conn_total 1133101
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1696331
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6208
telemt_desync_full_logged_total 2104
telemt_desync_suppressed_total 4104
telemt_desync_frames_bucket_total{bucket="1_2"} 1305
telemt_desync_frames_bucket_total{bucket="3_10"} 2417
telemt_desync_frames_bucket_total{bucket="gt_10"} 2486
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6359
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 5910
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 1702526
telemt_user_connections_current{user="hello"} 2912
telemt_user_octets_from_client{user="hello"} 19443469908 (18.11 GB)
telemt_user_octets_to_client{user="hello"} 490484415230 (456.80 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 991
telemt_user_unique_ips_recent_window{user="hello"} 506
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 46566.2 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2655134
telemt_connections_bad_total 587837
telemt_connections_current 3591
telemt_connections_me_current 3591
telemt_handshake_timeouts_total 52691
telemt_upstream_connect_attempt_total 8179
telemt_upstream_connect_success_total 8122
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 8179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6981
telemt_me_reconnect_success_total 5781
telemt_me_reader_eof_total 6146
telemt_me_idle_close_by_peer_total 6145
telemt_me_route_drop_no_conn_total 986468
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1757047
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7797
telemt_desync_full_logged_total 2428
telemt_desync_suppressed_total 5369
telemt_desync_frames_bucket_total{bucket="1_2"} 1533
telemt_desync_frames_bucket_total{bucket="3_10"} 3347
telemt_desync_frames_bucket_total{bucket="gt_10"} 2917
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 5904
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5757
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 1756124
telemt_user_connections_current{user="hello"} 3591
telemt_user_octets_from_client{user="hello"} 31524666132 (29.36 GB)
telemt_user_octets_to_client{user="hello"} 725033525324 (675.24 GB)
telemt_user_unique_ips_current{user="hello"} 1216
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 46579.0 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465325
telemt_connections_bad_total 18339
telemt_connections_current 876
telemt_connections_me_current 876
telemt_handshake_timeouts_total 3642
telemt_upstream_connect_attempt_total 11693
telemt_upstream_connect_success_total 11401
telemt_upstream_connect_fail_total 292
telemt_upstream_connect_attempts_per_request{bucket="1"} 11693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 292
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 14452
telemt_me_reconnect_success_total 9059
telemt_me_reader_eof_total 9595
telemt_me_idle_close_by_peer_total 9595
telemt_me_route_drop_no_conn_total 238317
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 420083
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 858
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 571
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9302
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 9029
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 420035
telemt_user_connections_current{user="hello"} 876
telemt_user_octets_from_client{user="hello"} 6861318716 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 160072040476 (149.08 GB)
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 46568.7 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1795747
telemt_connections_bad_total 152836
telemt_connections_current 3027
telemt_connections_me_current 3027
telemt_handshake_timeouts_total 70507
telemt_upstream_connect_attempt_total 9411
telemt_upstream_connect_success_total 9410
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8414
telemt_me_reconnect_success_total 7058
telemt_me_reader_eof_total 7476
telemt_me_idle_close_by_peer_total 7475
telemt_me_route_drop_no_conn_total 698890
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1485722
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8500
telemt_desync_full_logged_total 2741
telemt_desync_suppressed_total 5759
telemt_desync_frames_bucket_total{bucket="1_2"} 1599
telemt_desync_frames_bucket_total{bucket="3_10"} 3225
telemt_desync_frames_bucket_total{bucket="gt_10"} 3676
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7188
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7043
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 1484480
telemt_user_connections_current{user="hello"} 3027
telemt_user_octets_from_client{user="hello"} 20944504816 (19.51 GB)
telemt_user_octets_to_client{user="hello"} 709257031572 (660.55 GB)
telemt_user_unique_ips_current{user="hello"} 1038
telemt_user_unique_ips_recent_window{user="hello"} 426
```