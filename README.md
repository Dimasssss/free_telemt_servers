# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-23 05:30:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 116671.9 (32h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4143478
telemt_connections_bad_total 395561
telemt_connections_current 1615
telemt_connections_me_current 1615
telemt_handshake_timeouts_total 137263
telemt_upstream_connect_attempt_total 43425
telemt_upstream_connect_success_total 43424
telemt_upstream_connect_attempts_per_request{bucket="1"} 43424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1501
telemt_me_reconnect_success_total 681
telemt_me_reader_eof_total 702
telemt_me_idle_close_by_peer_total 702
telemt_me_route_drop_no_conn_total 3430442
telemt_me_route_drop_channel_closed_total 1328
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3392065
telemt_me_writer_pick_total{mode="p2c",result="full"} 18
telemt_me_endpoint_quarantine_total 829
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 914
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 14006
telemt_desync_full_logged_total 4451
telemt_desync_suppressed_total 9555
telemt_desync_frames_bucket_total{bucket="1_2"} 3645
telemt_desync_frames_bucket_total{bucket="3_10"} 5199
telemt_desync_frames_bucket_total{bucket="gt_10"} 5162
telemt_pool_swap_total 129
telemt_pool_force_close_total 3944
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 750
telemt_me_draining_writers_reap_progress_total 39780
telemt_me_writer_removed_unexpected_total 676
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2847
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37211
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3879
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35836
telemt_me_writer_teardown_success_total{mode="normal"} 40058
telemt_me_writer_teardown_noop_total 39793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79851
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 433.985464
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79851
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 750
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 611
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 3379493
telemt_user_connections_current{user="hello"} 1615
telemt_user_octets_from_client{user="hello"} 45260096748 (42.15 GB)
telemt_user_octets_to_client{user="hello"} 887812557604 (826.84 GB)
telemt_user_unique_ips_current{user="hello"} 622
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 130038.2 (36h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4151745
telemt_connections_bad_total 386155
telemt_connections_current 490
telemt_connections_me_current 490
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 107475
telemt_upstream_connect_attempt_total 81065
telemt_upstream_connect_success_total 80093
telemt_upstream_connect_fail_total 864
telemt_upstream_connect_attempts_per_request{bucket="1"} 80957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 864
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10948
telemt_me_reconnect_success_total 3913
telemt_me_reader_eof_total 3884
telemt_me_idle_close_by_peer_total 3884
telemt_me_route_drop_no_conn_total 3670080
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3291782
telemt_me_endpoint_quarantine_total 1063
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 55
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 55
telemt_me_single_endpoint_shadow_rotate_total 1025
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 13539
telemt_desync_full_logged_total 7632
telemt_desync_suppressed_total 5907
telemt_desync_frames_bucket_total{bucket="1_2"} 3086
telemt_desync_frames_bucket_total{bucket="3_10"} 5307
telemt_desync_frames_bucket_total{bucket="gt_10"} 5146
telemt_pool_swap_total 123
telemt_pool_force_close_total 3417
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 262
telemt_me_draining_writers_reap_progress_total 54480
telemt_me_writer_removed_unexpected_total 3804
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6886
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51440
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2932
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 485
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51063
telemt_me_writer_teardown_success_total{mode="normal"} 58326
telemt_me_writer_teardown_noop_total 54481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112807
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.950059
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112807
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 262
telemt_me_refill_failed_total 278
telemt_me_writer_restored_same_endpoint_total 3460
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 3306209
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 44431322875 (41.38 GB)
telemt_user_octets_to_client{user="hello"} 832345062249 (775.18 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 204898.1 (56h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16669206
telemt_connections_bad_total 1689170
telemt_connections_current 1659
telemt_connections_me_current 1659
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 408068
telemt_upstream_connect_attempt_total 92037
telemt_upstream_connect_success_total 91930
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 91947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45425
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1732
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3260
telemt_me_reconnect_success_total 1686
telemt_me_reader_eof_total 1647
telemt_me_idle_close_by_peer_total 1645
telemt_me_route_drop_no_conn_total 14116011
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13241159
telemt_me_endpoint_quarantine_total 1393
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1552
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 40
telemt_desync_total 55250
telemt_desync_full_logged_total 17661
telemt_desync_suppressed_total 37589
telemt_desync_frames_bucket_total{bucket="1_2"} 12320
telemt_desync_frames_bucket_total{bucket="3_10"} 21650
telemt_desync_frames_bucket_total{bucket="gt_10"} 21280
telemt_pool_swap_total 222
telemt_pool_force_close_total 7120
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1102
telemt_me_draining_writers_reap_progress_total 70863
telemt_me_writer_removed_unexpected_total 1580
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5945
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65784
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6650
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63743
telemt_me_writer_teardown_success_total{mode="normal"} 71729
telemt_me_writer_teardown_noop_total 70917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142646
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.185063
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142646
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1102
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1461
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 13240984
telemt_user_connections_current{user="hello"} 1659
telemt_user_octets_from_client{user="hello"} 200313979393 (186.56 GB)
telemt_user_octets_to_client{user="hello"} 3593433283963 (3.27 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 664
telemt_user_unique_ips_recent_window{user="hello"} 262
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 204899.3 (56h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12178819
telemt_connections_bad_total 1291963
telemt_connections_current 1067
telemt_connections_me_current 1067
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 352832
telemt_upstream_connect_attempt_total 106433
telemt_upstream_connect_success_total 105021
telemt_upstream_connect_fail_total 899
telemt_upstream_connect_attempts_per_request{bucket="1"} 105920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 899
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4710
telemt_me_reconnect_success_total 2022
telemt_me_reader_eof_total 1886
telemt_me_idle_close_by_peer_total 1886
telemt_me_route_drop_no_conn_total 4610852
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9006114
telemt_me_endpoint_quarantine_total 1397
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1569
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 39619
telemt_desync_full_logged_total 13360
telemt_desync_suppressed_total 26259
telemt_desync_frames_bucket_total{bucket="1_2"} 9836
telemt_desync_frames_bucket_total{bucket="3_10"} 15210
telemt_desync_frames_bucket_total{bucket="gt_10"} 14573
telemt_pool_swap_total 219
telemt_pool_force_close_total 6468
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 722
telemt_me_draining_writers_reap_progress_total 68947
telemt_me_writer_removed_unexpected_total 1916
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6044
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64682
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5956
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62479
telemt_me_writer_teardown_success_total{mode="normal"} 70726
telemt_me_writer_teardown_noop_total 68972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139698
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.691075
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139698
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 722
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1727
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8943659
telemt_user_connections_current{user="hello"} 1067
telemt_user_octets_from_client{user="hello"} 220265259468 (205.14 GB)
telemt_user_octets_to_client{user="hello"} 4030943784571 (3.67 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 204863.4 (56h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11323227
telemt_connections_bad_total 1037265
telemt_connections_current 1048
telemt_connections_me_current 1048
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 357173
telemt_upstream_connect_attempt_total 90870
telemt_upstream_connect_success_total 89294
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 89499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5903
telemt_me_reconnect_success_total 2486
telemt_me_reader_eof_total 2233
telemt_me_idle_close_by_peer_total 2232
telemt_me_route_drop_no_conn_total 5379683
telemt_me_route_drop_channel_closed_total 385
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8513957
telemt_me_endpoint_quarantine_total 1449
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1532
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 38689
telemt_desync_full_logged_total 12852
telemt_desync_suppressed_total 25837
telemt_desync_frames_bucket_total{bucket="1_2"} 9769
telemt_desync_frames_bucket_total{bucket="3_10"} 14818
telemt_desync_frames_bucket_total{bucket="gt_10"} 14102
telemt_pool_swap_total 215
telemt_pool_force_close_total 6352
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 763
telemt_me_draining_writers_reap_progress_total 69566
telemt_me_writer_removed_unexpected_total 2378
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6791
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65090
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5781
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63214
telemt_me_writer_teardown_success_total{mode="normal"} 71881
telemt_me_writer_teardown_noop_total 69637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141518
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.974398
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141518
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 763
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2167
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8505747
telemt_user_connections_current{user="hello"} 1048
telemt_user_octets_from_client{user="hello"} 194236547531 (180.90 GB)
telemt_user_octets_to_client{user="hello"} 3528828513989 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 75143.5 (20h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11675033
telemt_connections_bad_total 701836
telemt_connections_current 2069
telemt_connections_me_current 2069
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 318073
telemt_upstream_connect_attempt_total 67559
telemt_upstream_connect_success_total 63978
telemt_upstream_connect_fail_total 2315
telemt_upstream_connect_attempts_per_request{bucket="1"} 66293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6054
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2315
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8413
telemt_me_reconnect_success_total 1559
telemt_me_reader_eof_total 986
telemt_me_idle_close_by_peer_total 985
telemt_me_route_drop_no_conn_total 25376077
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9651868
telemt_me_endpoint_quarantine_total 588
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 213
telemt_me_single_endpoint_outage_reconnect_success_total 56
telemt_me_single_endpoint_quarantine_bypass_total 213
telemt_me_single_endpoint_shadow_rotate_total 606
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 17308
telemt_desync_full_logged_total 4823
telemt_desync_suppressed_total 12485
telemt_desync_frames_bucket_total{bucket="1_2"} 3347
telemt_desync_frames_bucket_total{bucket="3_10"} 7079
telemt_desync_frames_bucket_total{bucket="gt_10"} 6882
telemt_pool_swap_total 77
telemt_pool_force_close_total 2413
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 529
telemt_me_draining_writers_reap_progress_total 24949
telemt_me_writer_removed_unexpected_total 1443
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3230
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23114
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2071
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 342
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22536
telemt_me_writer_teardown_success_total{mode="normal"} 26344
telemt_me_writer_teardown_noop_total 24968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51312
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.055340
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51312
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 529
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 1000
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 9679392
telemt_user_connections_current{user="hello"} 2069
telemt_user_octets_from_client{user="hello"} 90843666227 (84.60 GB)
telemt_user_octets_to_client{user="hello"} 726474556221 (676.58 GB)
telemt_user_msgs_from_client{user="hello"} 71666
telemt_user_msgs_to_client{user="hello"} 62721
telemt_user_unique_ips_current{user="hello"} 719
telemt_user_unique_ips_recent_window{user="hello"} 319
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 204870.2 (56h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11291231
telemt_connections_bad_total 992470
telemt_connections_current 1514
telemt_connections_me_current 1514
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 253615
telemt_upstream_connect_attempt_total 119779
telemt_upstream_connect_success_total 118537
telemt_upstream_connect_fail_total 1065
telemt_upstream_connect_attempts_per_request{bucket="1"} 119602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1065
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73531
telemt_me_reconnect_success_total 3262
telemt_me_reader_eof_total 2957
telemt_me_idle_close_by_peer_total 2954
telemt_me_route_drop_no_conn_total 5322000
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8890284
telemt_me_endpoint_quarantine_total 1391
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1559
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 47353
telemt_desync_full_logged_total 16282
telemt_desync_suppressed_total 31071
telemt_desync_frames_bucket_total{bucket="1_2"} 9624
telemt_desync_frames_bucket_total{bucket="3_10"} 18156
telemt_desync_frames_bucket_total{bucket="gt_10"} 19573
telemt_pool_swap_total 211
telemt_pool_force_close_total 6073
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 684
telemt_me_draining_writers_reap_progress_total 73621
telemt_me_writer_removed_unexpected_total 2974
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7320
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69322
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5324
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67548
telemt_me_writer_teardown_success_total{mode="normal"} 76642
telemt_me_writer_teardown_noop_total 73622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 148108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 149528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 149947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 150220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 150254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 150257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 150257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 150260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 150264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 150264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 150264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 150264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 150264
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.364099
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 150264
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 684
telemt_me_refill_failed_total 4322
telemt_me_writer_restored_same_endpoint_total 2747
telemt_me_writer_restored_fallback_total 56
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8892917
telemt_user_connections_current{user="hello"} 1514
telemt_user_octets_from_client{user="hello"} 199173362569 (185.49 GB)
telemt_user_octets_to_client{user="hello"} 3404459831104 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 556
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 141706.5 (39h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12076982
telemt_connections_bad_total 493880
telemt_connections_current 1081
telemt_connections_me_current 1081
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4874706
telemt_upstream_connect_attempt_total 68785
telemt_upstream_connect_success_total 68295
telemt_upstream_connect_fail_total 477
telemt_upstream_connect_attempts_per_request{bucket="1"} 68772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 477
telemt_me_reconnect_attempts_total 49364
telemt_me_reconnect_success_total 1966
telemt_me_reader_eof_total 1651
telemt_me_idle_close_by_peer_total 1650
telemt_me_route_drop_no_conn_total 4144247
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5802555
telemt_me_endpoint_quarantine_total 977
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1095
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32639
telemt_desync_full_logged_total 11168
telemt_desync_suppressed_total 21471
telemt_desync_frames_bucket_total{bucket="1_2"} 6561
telemt_desync_frames_bucket_total{bucket="3_10"} 12853
telemt_desync_frames_bucket_total{bucket="gt_10"} 13225
telemt_pool_swap_total 151
telemt_pool_force_close_total 4265
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 53604
telemt_me_writer_removed_unexpected_total 1688
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4231
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51119
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3821
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49339
telemt_me_writer_teardown_success_total{mode="normal"} 55350
telemt_me_writer_teardown_noop_total 53611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108961
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.835975
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108961
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 2753
telemt_me_writer_restored_same_endpoint_total 1736
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5794399
telemt_user_connections_current{user="hello"} 1081
telemt_user_octets_from_client{user="hello"} 121821159600 (113.45 GB)
telemt_user_octets_to_client{user="hello"} 2255674763346 (2.05 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 122676.8 (34h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1699666
telemt_connections_bad_total 37571
telemt_connections_current 817
telemt_connections_me_current 817
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 36598
telemt_upstream_connect_attempt_total 57773
telemt_upstream_connect_success_total 57584
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 57738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 849
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2509
telemt_me_reconnect_success_total 1015
telemt_me_reader_eof_total 1011
telemt_me_idle_close_by_peer_total 1011
telemt_me_route_drop_no_conn_total 573993
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1509534
telemt_me_endpoint_quarantine_total 1046
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1011
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 10393
telemt_desync_full_logged_total 2940
telemt_desync_suppressed_total 7453
telemt_desync_frames_bucket_total{bucket="1_2"} 3278
telemt_desync_frames_bucket_total{bucket="3_10"} 3897
telemt_desync_frames_bucket_total{bucket="gt_10"} 3218
telemt_pool_swap_total 133
telemt_pool_force_close_total 3361
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 49268
telemt_me_writer_removed_unexpected_total 973
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3721
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46566
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3273
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45907
telemt_me_writer_teardown_success_total{mode="normal"} 50287
telemt_me_writer_teardown_noop_total 49272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99559
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.710312
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99559
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 869
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1505095
telemt_user_connections_current{user="hello"} 817
telemt_user_octets_from_client{user="hello"} 27635322957 (25.74 GB)
telemt_user_octets_to_client{user="hello"} 616007232139 (573.70 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 204874.7 (56h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13570213
telemt_connections_bad_total 1636661
telemt_connections_current 1456
telemt_connections_me_current 1456
telemt_handshake_timeouts_total 397767
telemt_upstream_connect_attempt_total 82643
telemt_upstream_connect_success_total 82277
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 82506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41461
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3246
telemt_me_reconnect_success_total 1623
telemt_me_reader_eof_total 1615
telemt_me_idle_close_by_peer_total 1615
telemt_me_route_drop_no_conn_total 4531308
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10235445
telemt_me_endpoint_quarantine_total 1515
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1559
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 42985
telemt_desync_full_logged_total 14021
telemt_desync_suppressed_total 28964
telemt_desync_frames_bucket_total{bucket="1_2"} 10469
telemt_desync_frames_bucket_total{bucket="3_10"} 15781
telemt_desync_frames_bucket_total{bucket="gt_10"} 16735
telemt_pool_swap_total 227
telemt_pool_force_close_total 5925
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 703
telemt_me_draining_writers_reap_progress_total 74831
telemt_me_writer_removed_unexpected_total 1544
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5747
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70689
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5751
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68906
telemt_me_writer_teardown_success_total{mode="normal"} 76436
telemt_me_writer_teardown_noop_total 74833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 148627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 150377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 150760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 151136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 151256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 151269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 151269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 151269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 151269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 151269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 151269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 151269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 151269
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.992156
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 151269
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 703
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1428
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 10201852
telemt_user_connections_current{user="hello"} 1456
telemt_user_octets_from_client{user="hello"} 197076639532 (183.54 GB)
telemt_user_octets_to_client{user="hello"} 4550632657928 (4.14 TB)
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 204871.4 (56h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11886197
telemt_connections_bad_total 1387654
telemt_connections_current 1304
telemt_connections_me_current 1304
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 320152
telemt_upstream_connect_attempt_total 110551
telemt_upstream_connect_success_total 109601
telemt_upstream_connect_fail_total 741
telemt_upstream_connect_attempts_per_request{bucket="1"} 110342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47115
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 741
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11119
telemt_me_reconnect_success_total 2766
telemt_me_reader_eof_total 2571
telemt_me_idle_close_by_peer_total 2570
telemt_me_seq_mismatch_total 107
telemt_me_route_drop_no_conn_total 5698252
telemt_me_route_drop_channel_closed_total 355
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9155158
telemt_me_endpoint_quarantine_total 1693
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1563
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 42596
telemt_desync_full_logged_total 13717
telemt_desync_suppressed_total 28879
telemt_desync_frames_bucket_total{bucket="1_2"} 11073
telemt_desync_frames_bucket_total{bucket="3_10"} 15646
telemt_desync_frames_bucket_total{bucket="gt_10"} 15877
telemt_pool_swap_total 217
telemt_pool_force_close_total 5675
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 75203
telemt_me_writer_removed_unexpected_total 2605
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7165
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70745
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5204
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69528
telemt_me_writer_teardown_success_total{mode="normal"} 77910
telemt_me_writer_teardown_noop_total 75208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 150375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 152195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 152749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 153068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 153118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 153118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 153118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 153118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 153118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 153118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 153118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 153118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 153118
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.841091
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 153118
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 434
telemt_me_writer_restored_same_endpoint_total 2206
telemt_me_writer_restored_fallback_total 142
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 9159582
telemt_user_connections_current{user="hello"} 1304
telemt_user_octets_from_client{user="hello"} 159456020044 (148.50 GB)
telemt_user_octets_to_client{user="hello"} 3585517494966 (3.26 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 178
```