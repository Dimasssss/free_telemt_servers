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

# Server Metrics 2026-03-17 11:35:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 60618.4 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 544315
telemt_connections_bad_total 4648
telemt_handshake_timeouts_total 16087
telemt_upstream_connect_attempt_total 14988
telemt_upstream_connect_success_total 14546
telemt_upstream_connect_fail_total 442
telemt_upstream_connect_attempts_per_request{bucket="1"} 14988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 442
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 10755
telemt_me_reconnect_success_total 9220
telemt_me_reader_eof_total 9794
telemt_me_idle_close_by_peer_total 9793
telemt_me_route_drop_no_conn_total 178064
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 491563
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3889
telemt_desync_full_logged_total 1025
telemt_desync_suppressed_total 2864
telemt_desync_frames_bucket_total{bucket="1_2"} 1128
telemt_desync_frames_bucket_total{bucket="3_10"} 1620
telemt_desync_frames_bucket_total{bucket="gt_10"} 1141
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9403
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 9198
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 493494
telemt_user_connections_current{user="hello"} 978
telemt_user_octets_from_client{user="hello"} 6755911231 (6.29 GB)
telemt_user_octets_to_client{user="hello"} 180647020347 (168.24 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 60869.8 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304085
telemt_connections_bad_total 12087
telemt_handshake_timeouts_total 17556
telemt_upstream_connect_attempt_total 15376
telemt_upstream_connect_success_total 15158
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 15376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 24472
telemt_me_reconnect_success_total 12138
telemt_me_reader_eof_total 13109
telemt_me_idle_close_by_peer_total 13109
telemt_me_route_drop_no_conn_total 113134
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259552
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 786
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 504
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 337
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 12655
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12122
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 259540
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 3041207536 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 94071956456 (87.61 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 60646.4 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179175
telemt_connections_bad_total 7716
telemt_handshake_timeouts_total 14557
telemt_upstream_connect_attempt_total 15927
telemt_upstream_connect_success_total 15845
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 14653
telemt_me_reconnect_success_total 12781
telemt_me_reader_eof_total 13661
telemt_me_idle_close_by_peer_total 13661
telemt_me_route_drop_no_conn_total 53413
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146575
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 540
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 398
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13019
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 12770
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 146478
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 13917963580 (12.96 GB)
telemt_user_octets_to_client{user="hello"} 42358980580 (39.45 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 60705.3 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405274
telemt_connections_bad_total 6812
telemt_handshake_timeouts_total 12100
telemt_upstream_connect_attempt_total 13870
telemt_upstream_connect_success_total 13740
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 13870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7201
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 12657
telemt_me_reconnect_success_total 10634
telemt_me_reader_eof_total 11319
telemt_me_idle_close_by_peer_total 11319
telemt_me_route_drop_no_conn_total 114061
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336485
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 994
telemt_desync_full_logged_total 360
telemt_desync_suppressed_total 634
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 332
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10870
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 10625
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 336418
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 4413814606 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 122722356937 (114.29 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 60677.0 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213075
telemt_connections_bad_total 52028
telemt_handshake_timeouts_total 3046
telemt_upstream_connect_attempt_total 17906
telemt_upstream_connect_success_total 17671
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 17906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28162
telemt_me_reconnect_success_total 14508
telemt_me_reader_eof_total 15539
telemt_me_idle_close_by_peer_total 15539
telemt_me_route_drop_no_conn_total 56082
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150918
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 898
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 724
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 15112
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 14500
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 604
telemt_user_connections_total{user="hello"} 150933
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 2105559943 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 64016309238 (59.62 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 60838.5 (16h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500428
telemt_connections_bad_total 51669
telemt_handshake_timeouts_total 4712
telemt_upstream_connect_attempt_total 12328
telemt_upstream_connect_success_total 12262
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 12328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 13121
telemt_me_reconnect_success_total 9228
telemt_me_reader_eof_total 9950
telemt_me_idle_close_by_peer_total 9950
telemt_me_route_drop_no_conn_total 335386
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 494573
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 741
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 465
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9492
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9214
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 416263
telemt_user_connections_current{user="hello"} 868
telemt_user_octets_from_client{user="hello"} 6125892448 (5.71 GB)
telemt_user_octets_to_client{user="hello"} 210186064636 (195.75 GB)
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 8605.3 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6264
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 4827
telemt_upstream_connect_success_total 4783
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 4827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 6302
telemt_me_reconnect_success_total 4184
telemt_me_reader_eof_total 4352
telemt_me_idle_close_by_peer_total 4352
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 2417
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5952
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4294
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 4175
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 6058
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 148012701 (141.16 MB)
telemt_user_octets_to_client{user="hello"} 19108100010 (17.80 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```