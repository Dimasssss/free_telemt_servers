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

# Server Metrics 2026-03-13 21:57:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 138265.7 (38h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 574289
telemt_connections_bad_total 17077
telemt_handshake_timeouts_total 12801
telemt_upstream_connect_attempt_total 35077
telemt_upstream_connect_success_total 34900
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 35077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5111
telemt_me_reconnect_attempts_total 32268
telemt_me_reconnect_success_total 27611
telemt_me_reader_eof_total 29483
telemt_me_idle_close_by_peer_total 29482
telemt_me_route_drop_no_conn_total 189360
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 494012
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1585
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1048
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 591
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 28065
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27595
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 493907
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 14858533622 (13.84 GB)
telemt_user_octets_to_client{user="hello"} 242942074508 (226.26 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 138158.5 (38h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292508
telemt_connections_bad_total 2138
telemt_handshake_timeouts_total 1918
telemt_upstream_connect_attempt_total 138809
telemt_upstream_connect_success_total 137795
telemt_upstream_connect_fail_total 1014
telemt_upstream_connect_attempts_per_request{bucket="1"} 138809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1014
telemt_me_keepalive_timeout_total 3697
telemt_me_reconnect_attempts_total 145585
telemt_me_reconnect_success_total 27578
telemt_me_reader_eof_total 32011
telemt_me_idle_close_by_peer_total 32011
telemt_me_route_drop_no_conn_total 87113
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174221
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
telemt_me_writer_removed_unexpected_total 31527
telemt_me_refill_failed_total 3682
telemt_me_writer_restored_same_endpoint_total 27561
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3949
telemt_user_connections_total{user="hello"} 277334
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 2937569779 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 85034493043 (79.19 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 138122.1 (38h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340325
telemt_connections_bad_total 2658
telemt_handshake_timeouts_total 27513
telemt_upstream_connect_attempt_total 36752
telemt_upstream_connect_success_total 36747
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 36752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19766
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2851
telemt_me_reconnect_attempts_total 31056
telemt_me_reconnect_success_total 29810
telemt_me_reader_eof_total 31985
telemt_me_idle_close_by_peer_total 31985
telemt_me_route_drop_no_conn_total 121103
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298184
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
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 30150
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29790
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 340
telemt_user_connections_total{user="hello"} 298085
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 12342895564 (11.50 GB)
telemt_user_octets_to_client{user="hello"} 123705916644 (115.21 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 138097.7 (38h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445116
telemt_connections_bad_total 15269
telemt_handshake_timeouts_total 4233
telemt_upstream_connect_attempt_total 64152
telemt_upstream_connect_success_total 53787
telemt_upstream_connect_fail_total 10365
telemt_upstream_connect_attempts_per_request{bucket="1"} 64152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19930
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 304
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10365
telemt_me_keepalive_timeout_total 4770
telemt_me_reconnect_attempts_total 130326
telemt_me_reconnect_success_total 27859
telemt_me_reader_eof_total 31841
telemt_me_idle_close_by_peer_total 31834
telemt_me_route_drop_no_conn_total 155253
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375676
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1589
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 1119
telemt_desync_frames_bucket_total{bucket="1_2"} 377
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 31412
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 27849
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3553
telemt_user_connections_total{user="hello"} 394518
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 8959971119 (8.34 GB)
telemt_user_octets_to_client{user="hello"} 150754983204 (140.40 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 88269.3 (24h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149420
telemt_connections_bad_total 22087
telemt_handshake_timeouts_total 1536
telemt_upstream_connect_attempt_total 32876
telemt_upstream_connect_success_total 32565
telemt_upstream_connect_fail_total 311
telemt_upstream_connect_attempts_per_request{bucket="1"} 32876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 311
telemt_me_keepalive_timeout_total 1301
telemt_me_reconnect_attempts_total 36658
telemt_me_reconnect_success_total 23261
telemt_me_reader_eof_total 24915
telemt_me_idle_close_by_peer_total 24915
telemt_me_route_drop_no_conn_total 45872
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116220
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 611
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 23900
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 23243
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 639
telemt_user_connections_total{user="hello"} 121114
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 1405664549 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 57139190551 (53.22 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 138053.8 (38h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 835506
telemt_connections_bad_total 27129
telemt_handshake_timeouts_total 25093
telemt_upstream_connect_attempt_total 28433
telemt_upstream_connect_success_total 28284
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 28433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 3121
telemt_me_reconnect_attempts_total 26081
telemt_me_reconnect_success_total 21430
telemt_me_reader_eof_total 22985
telemt_me_idle_close_by_peer_total 22982
telemt_me_route_drop_no_conn_total 398589
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 781840
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
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 21858
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21423
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 754699
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 13109158360 (12.21 GB)
telemt_user_octets_to_client{user="hello"} 375684223288 (349.88 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 30
```