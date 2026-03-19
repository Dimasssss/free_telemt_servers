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

# Server Metrics 2026-03-19 08:47:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 39514.7 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768110
telemt_connections_bad_total 76314
telemt_connections_current 1607
telemt_connections_me_current 1607
telemt_handshake_timeouts_total 32137
telemt_upstream_connect_attempt_total 7444
telemt_upstream_connect_success_total 7314
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 7444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 6504
telemt_me_reconnect_success_total 5350
telemt_me_reader_eof_total 5679
telemt_me_idle_close_by_peer_total 5678
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 218922
telemt_me_route_drop_channel_closed_total 87
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 586329
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3787
telemt_desync_full_logged_total 1106
telemt_desync_suppressed_total 2681
telemt_desync_frames_bucket_total{bucket="1_2"} 1274
telemt_desync_frames_bucket_total{bucket="3_10"} 1397
telemt_desync_frames_bucket_total{bucket="gt_10"} 1116
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5448
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5332
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 583344
telemt_user_connections_current{user="hello"} 1607
telemt_user_octets_from_client{user="hello"} 9258691080 (8.62 GB)
telemt_user_octets_to_client{user="hello"} 193263035796 (179.99 GB)
telemt_user_unique_ips_current{user="hello"} 539
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 39518.8 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1875035
telemt_connections_bad_total 105408
telemt_connections_current 4189
telemt_connections_me_current 4189
telemt_handshake_timeouts_total 43145
telemt_upstream_connect_attempt_total 7426
telemt_upstream_connect_success_total 7290
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 7426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 6466
telemt_me_reconnect_success_total 5305
telemt_me_reader_eof_total 5620
telemt_me_idle_close_by_peer_total 5620
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 818567
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1551368
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6865
telemt_desync_full_logged_total 2326
telemt_desync_suppressed_total 4539
telemt_desync_frames_bucket_total{bucket="1_2"} 1228
telemt_desync_frames_bucket_total{bucket="3_10"} 2617
telemt_desync_frames_bucket_total{bucket="gt_10"} 3020
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5437
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5283
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 1551133
telemt_user_connections_current{user="hello"} 4189
telemt_user_octets_from_client{user="hello"} 26404528008 (24.59 GB)
telemt_user_octets_to_client{user="hello"} 588274741668 (547.87 GB)
telemt_user_unique_ips_current{user="hello"} 1389
telemt_user_unique_ips_recent_window{user="hello"} 638
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 39516.3 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1583415
telemt_connections_bad_total 199979
telemt_connections_current 3096
telemt_connections_me_current 3096
telemt_handshake_timeouts_total 39417
telemt_upstream_connect_attempt_total 7022
telemt_upstream_connect_success_total 7022
telemt_upstream_connect_attempts_per_request{bucket="1"} 7022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 5071
telemt_me_reconnect_success_total 5040
telemt_me_reader_eof_total 5335
telemt_me_idle_close_by_peer_total 5335
telemt_me_route_drop_no_conn_total 716275
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1218015
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5684
telemt_desync_full_logged_total 1773
telemt_desync_suppressed_total 3911
telemt_desync_frames_bucket_total{bucket="1_2"} 1264
telemt_desync_frames_bucket_total{bucket="3_10"} 2047
telemt_desync_frames_bucket_total{bucket="gt_10"} 2373
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5132
telemt_me_writer_restored_same_endpoint_total 5024
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 1217535
telemt_user_connections_current{user="hello"} 3096
telemt_user_octets_from_client{user="hello"} 19902838168 (18.54 GB)
telemt_user_octets_to_client{user="hello"} 591195476704 (550.59 GB)
telemt_user_unique_ips_current{user="hello"} 1077
telemt_user_unique_ips_recent_window{user="hello"} 504
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 39569.2 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1643966
telemt_connections_bad_total 96712
telemt_connections_current 3014
telemt_connections_me_current 3014
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 42037
telemt_upstream_connect_attempt_total 15268
telemt_upstream_connect_success_total 15168
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 15268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4135
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7427
telemt_me_reconnect_success_total 5035
telemt_me_reader_eof_total 5344
telemt_me_idle_close_by_peer_total 5343
telemt_me_route_drop_no_conn_total 732638
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1185376
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4359
telemt_desync_full_logged_total 1498
telemt_desync_suppressed_total 2861
telemt_desync_frames_bucket_total{bucket="1_2"} 863
telemt_desync_frames_bucket_total{bucket="3_10"} 1713
telemt_desync_frames_bucket_total{bucket="gt_10"} 1783
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5290
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5011
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 1192176
telemt_user_connections_current{user="hello"} 3014
telemt_user_octets_from_client{user="hello"} 15192059036 (14.15 GB)
telemt_user_octets_to_client{user="hello"} 371652697486 (346.13 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 992
telemt_user_unique_ips_recent_window{user="hello"} 472
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 39512.5 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1943431
telemt_connections_bad_total 497170
telemt_connections_current 3338
telemt_connections_me_current 3338
telemt_handshake_timeouts_total 40609
telemt_upstream_connect_attempt_total 6743
telemt_upstream_connect_success_total 6696
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 6743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 4760
telemt_me_reconnect_success_total 4722
telemt_me_reader_eof_total 5013
telemt_me_idle_close_by_peer_total 5013
telemt_me_route_drop_no_conn_total 524208
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1209367
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5942
telemt_desync_full_logged_total 1845
telemt_desync_suppressed_total 4097
telemt_desync_frames_bucket_total{bucket="1_2"} 1200
telemt_desync_frames_bucket_total{bucket="3_10"} 2646
telemt_desync_frames_bucket_total{bucket="gt_10"} 2096
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 4790
telemt_me_writer_restored_same_endpoint_total 4698
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 1208763
telemt_user_connections_current{user="hello"} 3338
telemt_user_octets_from_client{user="hello"} 23861705132 (22.22 GB)
telemt_user_octets_to_client{user="hello"} 559743564740 (521.30 GB)
telemt_user_unique_ips_current{user="hello"} 1145
telemt_user_unique_ips_recent_window{user="hello"} 505
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 39524.4 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334164
telemt_connections_bad_total 14743
telemt_connections_current 836
telemt_connections_me_current 836
telemt_handshake_timeouts_total 2849
telemt_upstream_connect_attempt_total 10093
telemt_upstream_connect_success_total 9831
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 10093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 13236
telemt_me_reconnect_success_total 7856
telemt_me_reader_eof_total 8333
telemt_me_idle_close_by_peer_total 8333
telemt_me_route_drop_no_conn_total 154243
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299791
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 440
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 135
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 8081
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7826
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 299760
telemt_user_connections_current{user="hello"} 836
telemt_user_octets_from_client{user="hello"} 4288439336 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 130469755668 (121.51 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 39514.9 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1293226
telemt_connections_bad_total 111847
telemt_connections_current 3146
telemt_connections_me_current 3146
telemt_handshake_timeouts_total 57131
telemt_upstream_connect_attempt_total 7917
telemt_upstream_connect_success_total 7916
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 7283
telemt_me_reconnect_success_total 5939
telemt_me_reader_eof_total 6302
telemt_me_idle_close_by_peer_total 6301
telemt_me_route_drop_no_conn_total 504513
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1074404
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6332
telemt_desync_full_logged_total 2077
telemt_desync_suppressed_total 4255
telemt_desync_frames_bucket_total{bucket="1_2"} 1192
telemt_desync_frames_bucket_total{bucket="3_10"} 2392
telemt_desync_frames_bucket_total{bucket="gt_10"} 2748
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6049
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5924
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 1073326
telemt_user_connections_current{user="hello"} 3146
telemt_user_octets_from_client{user="hello"} 14912153636 (13.89 GB)
telemt_user_octets_to_client{user="hello"} 539954171244 (502.87 GB)
telemt_user_unique_ips_current{user="hello"} 1035
telemt_user_unique_ips_recent_window{user="hello"} 450
```