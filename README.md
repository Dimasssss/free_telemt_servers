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

# Server Metrics 2026-03-19 09:53:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 43494.9 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 931339
telemt_connections_bad_total 82934
telemt_connections_current 1554
telemt_connections_me_current 1554
telemt_handshake_timeouts_total 34846
telemt_upstream_connect_attempt_total 8282
telemt_upstream_connect_success_total 8137
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 8282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 7103
telemt_me_reconnect_success_total 5945
telemt_me_reader_eof_total 6305
telemt_me_idle_close_by_peer_total 6304
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 311908
telemt_me_route_drop_channel_closed_total 125
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 718865
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4359
telemt_desync_full_logged_total 1320
telemt_desync_suppressed_total 3039
telemt_desync_frames_bucket_total{bucket="1_2"} 1452
telemt_desync_frames_bucket_total{bucket="3_10"} 1600
telemt_desync_frames_bucket_total{bucket="gt_10"} 1307
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6054
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5925
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 713280
telemt_user_connections_current{user="hello"} 1554
telemt_user_octets_from_client{user="hello"} 11295254304 (10.52 GB)
telemt_user_octets_to_client{user="hello"} 228171839968 (212.50 GB)
telemt_user_unique_ips_current{user="hello"} 552
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 43498.8 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2307231
telemt_connections_bad_total 146256
telemt_connections_current 4169
telemt_connections_me_current 4169
telemt_handshake_timeouts_total 51637
telemt_upstream_connect_attempt_total 8307
telemt_upstream_connect_success_total 8153
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 8307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8289
telemt_me_reconnect_success_total 5941
telemt_me_reader_eof_total 6325
telemt_me_idle_close_by_peer_total 6325
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1005956
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1901929
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8763
telemt_desync_full_logged_total 2905
telemt_desync_suppressed_total 5858
telemt_desync_frames_bucket_total{bucket="1_2"} 1606
telemt_desync_frames_bucket_total{bucket="3_10"} 3409
telemt_desync_frames_bucket_total{bucket="gt_10"} 3748
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6121
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 5919
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 1901668
telemt_user_connections_current{user="hello"} 4169
telemt_user_octets_from_client{user="hello"} 30509813472 (28.41 GB)
telemt_user_octets_to_client{user="hello"} 696512365208 (648.68 GB)
telemt_user_unique_ips_current{user="hello"} 1439
telemt_user_unique_ips_recent_window{user="hello"} 607
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 43495.9 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1935830
telemt_connections_bad_total 234166
telemt_connections_current 3188
telemt_connections_me_current 3188
telemt_handshake_timeouts_total 46390
telemt_upstream_connect_attempt_total 7800
telemt_upstream_connect_success_total 7800
telemt_upstream_connect_attempts_per_request{bucket="1"} 7800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5624
telemt_me_reconnect_success_total 5589
telemt_me_reader_eof_total 5916
telemt_me_idle_close_by_peer_total 5916
telemt_me_route_drop_no_conn_total 898088
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1506023
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6785
telemt_desync_full_logged_total 2142
telemt_desync_suppressed_total 4643
telemt_desync_frames_bucket_total{bucket="1_2"} 1512
telemt_desync_frames_bucket_total{bucket="3_10"} 2496
telemt_desync_frames_bucket_total{bucket="gt_10"} 2777
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 5686
telemt_me_writer_restored_same_endpoint_total 5573
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 1504614
telemt_user_connections_current{user="hello"} 3188
telemt_user_octets_from_client{user="hello"} 22956595348 (21.38 GB)
telemt_user_octets_to_client{user="hello"} 690258963900 (642.85 GB)
telemt_user_unique_ips_current{user="hello"} 1057
telemt_user_unique_ips_recent_window{user="hello"} 452
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 43549.2 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1995917
telemt_connections_bad_total 108845
telemt_connections_current 2984
telemt_connections_me_current 2984
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 51740
telemt_upstream_connect_attempt_total 16015
telemt_upstream_connect_success_total 15891
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 16015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 7944
telemt_me_reconnect_success_total 5519
telemt_me_reader_eof_total 5865
telemt_me_idle_close_by_peer_total 5864
telemt_me_route_drop_no_conn_total 1002393
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1498511
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5480
telemt_desync_full_logged_total 1863
telemt_desync_suppressed_total 3617
telemt_desync_frames_bucket_total{bucket="1_2"} 1132
telemt_desync_frames_bucket_total{bucket="3_10"} 2146
telemt_desync_frames_bucket_total{bucket="gt_10"} 2202
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5798
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5495
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 1505175
telemt_user_connections_current{user="hello"} 2984
telemt_user_octets_from_client{user="hello"} 17628952040 (16.42 GB)
telemt_user_octets_to_client{user="hello"} 437115786214 (407.10 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1014
telemt_user_unique_ips_recent_window{user="hello"} 469
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 43492.7 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2318325
telemt_connections_bad_total 550049
telemt_connections_current 3760
telemt_connections_me_current 3760
telemt_handshake_timeouts_total 48762
telemt_upstream_connect_attempt_total 7597
telemt_upstream_connect_success_total 7544
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 7597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 5386
telemt_me_reconnect_success_total 5341
telemt_me_reader_eof_total 5652
telemt_me_idle_close_by_peer_total 5652
telemt_me_route_drop_no_conn_total 672211
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1493894
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6904
telemt_desync_full_logged_total 2147
telemt_desync_suppressed_total 4757
telemt_desync_frames_bucket_total{bucket="1_2"} 1376
telemt_desync_frames_bucket_total{bucket="3_10"} 3019
telemt_desync_frames_bucket_total{bucket="gt_10"} 2509
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5420
telemt_me_writer_restored_same_endpoint_total 5317
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 1493057
telemt_user_connections_current{user="hello"} 3760
telemt_user_octets_from_client{user="hello"} 27999388628 (26.08 GB)
telemt_user_octets_to_client{user="hello"} 654422698464 (609.48 GB)
telemt_user_unique_ips_current{user="hello"} 1240
telemt_user_unique_ips_recent_window{user="hello"} 556
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 43504.6 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414618
telemt_connections_bad_total 18020
telemt_connections_current 899
telemt_connections_me_current 899
telemt_handshake_timeouts_total 3309
telemt_upstream_connect_attempt_total 11018
telemt_upstream_connect_success_total 10738
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 11018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 13922
telemt_me_reconnect_success_total 8534
telemt_me_reader_eof_total 9054
telemt_me_idle_close_by_peer_total 9054
telemt_me_route_drop_no_conn_total 210243
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372602
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 645
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 426
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 222
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 8772
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8504
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 372573
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 5764376116 (5.37 GB)
telemt_user_octets_to_client{user="hello"} 146841011264 (136.76 GB)
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 43495.0 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1570574
telemt_connections_bad_total 132766
telemt_connections_current 3124
telemt_connections_me_current 3124
telemt_handshake_timeouts_total 66869
telemt_upstream_connect_attempt_total 8842
telemt_upstream_connect_success_total 8841
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 7981
telemt_me_reconnect_success_total 6629
telemt_me_reader_eof_total 7026
telemt_me_idle_close_by_peer_total 7025
telemt_me_route_drop_no_conn_total 611298
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1311525
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7426
telemt_desync_full_logged_total 2432
telemt_desync_suppressed_total 4994
telemt_desync_frames_bucket_total{bucket="1_2"} 1409
telemt_desync_frames_bucket_total{bucket="3_10"} 2792
telemt_desync_frames_bucket_total{bucket="gt_10"} 3225
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6750
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6614
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 1310376
telemt_user_connections_current{user="hello"} 3124
telemt_user_octets_from_client{user="hello"} 17961058952 (16.73 GB)
telemt_user_octets_to_client{user="hello"} 636401984040 (592.70 GB)
telemt_user_unique_ips_current{user="hello"} 1008
telemt_user_unique_ips_recent_window{user="hello"} 417
```