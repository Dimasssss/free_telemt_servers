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

# Server Metrics 2026-03-16 11:23:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 133749.1 (37h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 723983
telemt_connections_bad_total 53849
telemt_handshake_timeouts_total 23161
telemt_upstream_connect_attempt_total 30975
telemt_upstream_connect_success_total 30827
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 30975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 38412
telemt_me_reconnect_success_total 24186
telemt_me_reader_eof_total 26111
telemt_me_idle_close_by_peer_total 26111
telemt_me_route_drop_no_conn_total 599012
telemt_me_route_drop_channel_closed_total 91
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 667331
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3086
telemt_desync_full_logged_total 1181
telemt_desync_suppressed_total 1905
telemt_desync_frames_bucket_total{bucket="1_2"} 669
telemt_desync_frames_bucket_total{bucket="3_10"} 1219
telemt_desync_frames_bucket_total{bucket="gt_10"} 1198
telemt_pool_swap_total 122
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24890
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 24151
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 704
telemt_user_connections_total{user="hello"} 603865
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 11559144496 (10.77 GB)
telemt_user_octets_to_client{user="hello"} 355706090540 (331.28 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 133756.3 (37h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292634
telemt_connections_bad_total 3805
telemt_handshake_timeouts_total 18499
telemt_upstream_connect_attempt_total 35908
telemt_upstream_connect_success_total 35801
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 35908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 826
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1681
telemt_me_reconnect_attempts_total 38887
telemt_me_reconnect_success_total 28536
telemt_me_reader_eof_total 30580
telemt_me_idle_close_by_peer_total 30579
telemt_me_route_drop_no_conn_total 141000
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259027
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 29263
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 28520
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 727
telemt_user_connections_total{user="hello"} 258739
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 5368686373 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 132430956288 (123.34 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 133748.9 (37h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287836
telemt_connections_bad_total 5914
telemt_handshake_timeouts_total 7693
telemt_upstream_connect_attempt_total 37238
telemt_upstream_connect_success_total 37230
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 37238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 37942
telemt_me_reconnect_success_total 30510
telemt_me_reader_eof_total 32765
telemt_me_idle_close_by_peer_total 32764
telemt_me_route_drop_no_conn_total 98722
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234740
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 31050
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 30502
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 234379
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 18787450013 (17.50 GB)
telemt_user_octets_to_client{user="hello"} 126777893572 (118.07 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 133748.6 (37h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428968
telemt_connections_bad_total 1442
telemt_handshake_timeouts_total 3942
telemt_upstream_connect_attempt_total 30889
telemt_upstream_connect_success_total 30845
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 30889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 29183
telemt_me_reconnect_success_total 24181
telemt_me_reader_eof_total 25916
telemt_me_idle_close_by_peer_total 25915
telemt_me_route_drop_no_conn_total 146915
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 397387
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1480
telemt_desync_full_logged_total 496
telemt_desync_suppressed_total 984
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 633
telemt_desync_frames_bucket_total{bucket="gt_10"} 552
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 24662
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 24170
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 397252
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 6329176082 (5.89 GB)
telemt_user_octets_to_client{user="hello"} 153020994304 (142.51 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 108819.9 (30h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266825
telemt_connections_bad_total 45430
telemt_handshake_timeouts_total 4372
telemt_upstream_connect_attempt_total 31104
telemt_upstream_connect_success_total 30937
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 31104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 120965
telemt_me_reconnect_success_total 25364
telemt_me_reader_eof_total 26932
telemt_me_idle_close_by_peer_total 26932
telemt_me_route_drop_no_conn_total 81567
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208788
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 698
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 529
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 285
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 25614
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 25260
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 208409
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 2753784289 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 93350125719 (86.94 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 133748.1 (37h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 939608
telemt_connections_bad_total 73496
telemt_handshake_timeouts_total 10990
telemt_upstream_connect_attempt_total 28224
telemt_upstream_connect_success_total 28075
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 28224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 24020
telemt_me_reconnect_success_total 21404
telemt_me_reader_eof_total 22847
telemt_me_idle_close_by_peer_total 22846
telemt_me_route_drop_no_conn_total 694641
telemt_me_route_drop_channel_closed_total 127
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 922706
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 548
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 387
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 21742
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 21377
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 781317
telemt_user_connections_current{user="hello"} 762
telemt_user_octets_from_client{user="hello"} 16270458768 (15.15 GB)
telemt_user_octets_to_client{user="hello"} 452456094928 (421.38 GB)
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 116
```