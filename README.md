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

# Server Metrics 2026-03-14 12:08:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 189279.6 (52h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 747559
telemt_connections_bad_total 35291
telemt_handshake_timeouts_total 14417
telemt_upstream_connect_attempt_total 48076
telemt_upstream_connect_success_total 47837
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 48076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25788
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6337
telemt_me_reconnect_attempts_total 43782
telemt_me_reconnect_success_total 38015
telemt_me_reader_eof_total 40646
telemt_me_idle_close_by_peer_total 40645
telemt_me_route_drop_no_conn_total 246212
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 641413
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2730
telemt_desync_full_logged_total 912
telemt_desync_suppressed_total 1818
telemt_desync_frames_bucket_total{bucket="1_2"} 562
telemt_desync_frames_bucket_total{bucket="3_10"} 1025
telemt_desync_frames_bucket_total{bucket="gt_10"} 1143
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 38602
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37995
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 587
telemt_user_connections_total{user="hello"} 641319
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 17781284550 (16.56 GB)
telemt_user_octets_to_client{user="hello"} 308049189860 (286.89 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 189172.5 (52h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 370666
telemt_connections_bad_total 2847
telemt_handshake_timeouts_total 3341
telemt_upstream_connect_attempt_total 157847
telemt_upstream_connect_success_total 156453
telemt_upstream_connect_fail_total 1394
telemt_upstream_connect_attempts_per_request{bucket="1"} 157847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40178
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2520
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1394
telemt_me_keepalive_timeout_total 5710
telemt_me_reconnect_attempts_total 196530
telemt_me_reconnect_success_total 41901
telemt_me_reader_eof_total 47823
telemt_me_idle_close_by_peer_total 47823
telemt_me_route_drop_no_conn_total 127789
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245091
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 47133
telemt_me_refill_failed_total 4824
telemt_me_writer_restored_same_endpoint_total 41883
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5232
telemt_user_connections_total{user="hello"} 349984
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 3547472679 (3.30 GB)
telemt_user_octets_to_client{user="hello"} 112714066582 (104.97 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 189136.0 (52h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428076
telemt_connections_bad_total 3319
telemt_handshake_timeouts_total 36584
telemt_upstream_connect_attempt_total 50441
telemt_upstream_connect_success_total 50432
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 50441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4296
telemt_me_reconnect_attempts_total 42205
telemt_me_reconnect_success_total 40881
telemt_me_reader_eof_total 43921
telemt_me_idle_close_by_peer_total 43921
telemt_me_route_drop_no_conn_total 156632
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372826
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 146
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 41373
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 40860
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 372584
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 16179895854 (15.07 GB)
telemt_user_octets_to_client{user="hello"} 163206762931 (152.00 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 189112.0 (52h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 543869
telemt_connections_bad_total 16777
telemt_handshake_timeouts_total 5302
telemt_upstream_connect_attempt_total 80898
telemt_upstream_connect_success_total 70185
telemt_upstream_connect_fail_total 10713
telemt_upstream_connect_attempts_per_request{bucket="1"} 80898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28993
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 391
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10713
telemt_me_keepalive_timeout_total 5848
telemt_me_reconnect_attempts_total 156364
telemt_me_reconnect_success_total 41721
telemt_me_reader_eof_total 46632
telemt_me_idle_close_by_peer_total 46624
telemt_me_route_drop_no_conn_total 196957
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 466524
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2166
telemt_desync_full_logged_total 634
telemt_desync_suppressed_total 1532
telemt_desync_frames_bucket_total{bucket="1_2"} 501
telemt_desync_frames_bucket_total{bucket="3_10"} 825
telemt_desync_frames_bucket_total{bucket="gt_10"} 840
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 45781
telemt_me_refill_failed_total 3574
telemt_me_writer_restored_same_endpoint_total 41711
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4060
telemt_user_connections_total{user="hello"} 485389
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 10260507163 (9.56 GB)
telemt_user_octets_to_client{user="hello"} 198408027912 (184.78 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 139283.2 (38h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236578
telemt_connections_bad_total 38006
telemt_handshake_timeouts_total 2159
telemt_upstream_connect_attempt_total 49002
telemt_upstream_connect_success_total 48509
telemt_upstream_connect_fail_total 493
telemt_upstream_connect_attempts_per_request{bucket="1"} 49002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 493
telemt_me_keepalive_timeout_total 3129
telemt_me_reconnect_attempts_total 53605
telemt_me_reconnect_success_total 36692
telemt_me_reader_eof_total 39241
telemt_me_idle_close_by_peer_total 39241
telemt_me_route_drop_no_conn_total 71664
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185184
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 614
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 37567
telemt_me_refill_failed_total 524
telemt_me_writer_restored_same_endpoint_total 36674
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 875
telemt_user_connections_total{user="hello"} 189940
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 2759130333 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 87021296727 (81.04 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 189067.6 (52h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1103283
telemt_connections_bad_total 37679
telemt_handshake_timeouts_total 27238
telemt_upstream_connect_attempt_total 39404
telemt_upstream_connect_success_total 39197
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 39404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20587
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 5206
telemt_me_reconnect_attempts_total 34534
telemt_me_reconnect_success_total 29840
telemt_me_reader_eof_total 31995
telemt_me_idle_close_by_peer_total 31992
telemt_me_route_drop_no_conn_total 518635
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1023248
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 30365
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29833
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 995833
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 21310056236 (19.85 GB)
telemt_user_octets_to_client{user="hello"} 499627628752 (465.31 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 68
```