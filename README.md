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

# Server Metrics 2026-03-22 22:07:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 90081.8 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3288687
telemt_connections_bad_total 245561
telemt_connections_current 758
telemt_connections_me_current 758
telemt_handshake_timeouts_total 104267
telemt_upstream_connect_attempt_total 33087
telemt_upstream_connect_success_total 33086
telemt_upstream_connect_attempts_per_request{bucket="1"} 33086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1319
telemt_me_reconnect_success_total 548
telemt_me_reader_eof_total 562
telemt_me_idle_close_by_peer_total 562
telemt_me_route_drop_no_conn_total 2957730
telemt_me_route_drop_channel_closed_total 1226
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2766453
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 607
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 698
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_me_writers_warm_current 35
telemt_desync_total 11878
telemt_desync_full_logged_total 3723
telemt_desync_suppressed_total 8155
telemt_desync_frames_bucket_total{bucket="1_2"} 3218
telemt_desync_frames_bucket_total{bucket="3_10"} 4342
telemt_desync_frames_bucket_total{bucket="gt_10"} 4318
telemt_pool_swap_total 99
telemt_pool_force_close_total 3096
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 627
telemt_me_draining_writers_reap_progress_total 30239
telemt_me_writer_removed_unexpected_total 544
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2186
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28263
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3041
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27143
telemt_me_writer_teardown_success_total{mode="normal"} 30449
telemt_me_writer_teardown_noop_total 30250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60699
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.465231
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60699
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 627
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 488
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2755850
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 39594264812 (36.88 GB)
telemt_user_octets_to_client{user="hello"} 744555632824 (693.42 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 103448.1 (28h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3931198
telemt_connections_bad_total 353216
telemt_connections_current 857
telemt_connections_me_current 857
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99599
telemt_upstream_connect_attempt_total 62304
telemt_upstream_connect_success_total 61550
telemt_upstream_connect_fail_total 668
telemt_upstream_connect_attempts_per_request{bucket="1"} 62218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 668
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 7646
telemt_me_reconnect_success_total 3030
telemt_me_reader_eof_total 2995
telemt_me_idle_close_by_peer_total 2995
telemt_me_route_drop_no_conn_total 3631523
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3129924
telemt_me_endpoint_quarantine_total 770
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 799
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_me_writers_active_current 127
telemt_desync_total 12724
telemt_desync_full_logged_total 7128
telemt_desync_suppressed_total 5596
telemt_desync_frames_bucket_total{bucket="1_2"} 2877
telemt_desync_frames_bucket_total{bucket="3_10"} 4992
telemt_desync_frames_bucket_total{bucket="gt_10"} 4855
telemt_pool_swap_total 95
telemt_pool_force_close_total 2879
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 41552
telemt_me_writer_removed_unexpected_total 2934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5279
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39231
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38673
telemt_me_writer_teardown_success_total{mode="normal"} 44510
telemt_me_writer_teardown_noop_total 41553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86063
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.412311
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86063
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 182
telemt_me_writer_restored_same_endpoint_total 2704
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 3140587
telemt_user_connections_current{user="hello"} 857
telemt_user_octets_from_client{user="hello"} 42091783531 (39.20 GB)
telemt_user_octets_to_client{user="hello"} 773397296902 (720.28 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 178307.9 (49h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16162164
telemt_connections_bad_total 1590336
telemt_connections_current 1106
telemt_connections_me_current 1106
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 395861
telemt_upstream_connect_attempt_total 79133
telemt_upstream_connect_success_total 79033
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 79050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1698
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2863
telemt_me_reconnect_success_total 1494
telemt_me_reader_eof_total 1440
telemt_me_idle_close_by_peer_total 1438
telemt_me_route_drop_no_conn_total 14024090
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12864972
telemt_me_endpoint_quarantine_total 1154
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1330
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
telemt_desync_total 53178
telemt_desync_full_logged_total 16835
telemt_desync_suppressed_total 36343
telemt_desync_frames_bucket_total{bucket="1_2"} 11818
telemt_desync_frames_bucket_total{bucket="3_10"} 20711
telemt_desync_frames_bucket_total{bucket="gt_10"} 20649
telemt_pool_swap_total 193
telemt_pool_force_close_total 6440
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1042
telemt_me_draining_writers_reap_progress_total 58983
telemt_me_writer_removed_unexpected_total 1389
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5144
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54498
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5970
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52543
telemt_me_writer_teardown_success_total{mode="normal"} 59642
telemt_me_writer_teardown_noop_total 59036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118678
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 316.206208
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118678
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1042
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1292
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 12865257
telemt_user_connections_current{user="hello"} 1106
telemt_user_octets_from_client{user="hello"} 189693447577 (176.67 GB)
telemt_user_octets_to_client{user="hello"} 3453066996343 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 508
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 178309.2 (49h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11726409
telemt_connections_bad_total 1199310
telemt_connections_current 873
telemt_connections_me_current 873
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343665
telemt_upstream_connect_attempt_total 93609
telemt_upstream_connect_success_total 92300
telemt_upstream_connect_fail_total 862
telemt_upstream_connect_attempts_per_request{bucket="1"} 93162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38134
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3793
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 862
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4314
telemt_me_reconnect_success_total 1805
telemt_me_reader_eof_total 1666
telemt_me_idle_close_by_peer_total 1666
telemt_me_route_drop_no_conn_total 4538676
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8724616
telemt_me_endpoint_quarantine_total 1149
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1352
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 38549
telemt_desync_full_logged_total 12964
telemt_desync_suppressed_total 25585
telemt_desync_frames_bucket_total{bucket="1_2"} 9522
telemt_desync_frames_bucket_total{bucket="3_10"} 14819
telemt_desync_frames_bucket_total{bucket="gt_10"} 14208
telemt_pool_swap_total 190
telemt_pool_force_close_total 5812
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 57331
telemt_me_writer_removed_unexpected_total 1701
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5275
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53608
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5300
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51519
telemt_me_writer_teardown_success_total{mode="normal"} 58883
telemt_me_writer_teardown_noop_total 57356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116239
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.240763
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116239
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1537
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8662483
telemt_user_connections_current{user="hello"} 873
telemt_user_octets_from_client{user="hello"} 216937313068 (202.04 GB)
telemt_user_octets_to_client{user="hello"} 3924811914275 (3.57 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 178274.9 (49h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10945116
telemt_connections_bad_total 951754
telemt_connections_current 622
telemt_connections_me_current 622
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344813
telemt_upstream_connect_attempt_total 77591
telemt_upstream_connect_success_total 76111
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 76315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2314
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5470
telemt_me_reconnect_success_total 2270
telemt_me_reader_eof_total 2008
telemt_me_idle_close_by_peer_total 2007
telemt_me_route_drop_no_conn_total 5320080
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8283660
telemt_me_endpoint_quarantine_total 1219
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1307
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 67
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
telemt_me_writers_active_current 90
telemt_me_writers_warm_current 16
telemt_desync_total 37858
telemt_desync_full_logged_total 12546
telemt_desync_suppressed_total 25312
telemt_desync_frames_bucket_total{bucket="1_2"} 9565
telemt_desync_frames_bucket_total{bucket="3_10"} 14479
telemt_desync_frames_bucket_total{bucket="gt_10"} 13814
telemt_pool_swap_total 185
telemt_pool_force_close_total 5722
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 726
telemt_me_draining_writers_reap_progress_total 57570
telemt_me_writer_removed_unexpected_total 2163
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5955
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53705
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5157
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51848
telemt_me_writer_teardown_success_total{mode="normal"} 59660
telemt_me_writer_teardown_noop_total 57641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117301
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.270127
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117301
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 726
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 1970
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 8275666
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 191984507317 (178.80 GB)
telemt_user_octets_to_client{user="hello"} 3442772461929 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 48553.4 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11050771
telemt_connections_bad_total 666908
telemt_connections_current 1264
telemt_connections_me_current 1264
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 250127
telemt_upstream_connect_attempt_total 51149
telemt_upstream_connect_success_total 48595
telemt_upstream_connect_fail_total 1737
telemt_upstream_connect_attempts_per_request{bucket="1"} 50332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16176
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5987
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1737
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7052
telemt_me_reconnect_success_total 1041
telemt_me_reader_eof_total 653
telemt_me_idle_close_by_peer_total 652
telemt_me_route_drop_no_conn_total 25257870
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9178503
telemt_me_endpoint_quarantine_total 335
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 381
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 15734
telemt_desync_full_logged_total 4173
telemt_desync_suppressed_total 11561
telemt_desync_frames_bucket_total{bucket="1_2"} 3007
telemt_desync_frames_bucket_total{bucket="3_10"} 6364
telemt_desync_frames_bucket_total{bucket="gt_10"} 6363
telemt_pool_swap_total 49
telemt_pool_force_close_total 1711
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 452
telemt_me_draining_writers_reap_progress_total 14247
telemt_me_writer_removed_unexpected_total 930
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2051
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13084
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1405
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12536
telemt_me_writer_teardown_success_total{mode="normal"} 15135
telemt_me_writer_teardown_noop_total 14266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29401
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.300565
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29401
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 452
telemt_me_refill_failed_total 327
telemt_me_writer_restored_same_endpoint_total 681
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 9203198
telemt_user_connections_current{user="hello"} 1264
telemt_user_octets_from_client{user="hello"} 85551472452 (79.68 GB)
telemt_user_octets_to_client{user="hello"} 560765537550 (522.25 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 178280.0 (49h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10862457
telemt_connections_bad_total 916496
telemt_connections_current 904
telemt_connections_me_current 904
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 238934
telemt_upstream_connect_attempt_total 106428
telemt_upstream_connect_success_total 105318
telemt_upstream_connect_fail_total 942
telemt_upstream_connect_attempts_per_request{bucket="1"} 106260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40092
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 942
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72605
telemt_me_reconnect_success_total 2936
telemt_me_reader_eof_total 2634
telemt_me_idle_close_by_peer_total 2632
telemt_me_route_drop_no_conn_total 5239392
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8584666
telemt_me_endpoint_quarantine_total 1171
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1333
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 29
telemt_desync_total 45805
telemt_desync_full_logged_total 15665
telemt_desync_suppressed_total 30140
telemt_desync_frames_bucket_total{bucket="1_2"} 9290
telemt_desync_frames_bucket_total{bucket="3_10"} 17526
telemt_desync_frames_bucket_total{bucket="gt_10"} 18989
telemt_pool_swap_total 181
telemt_pool_force_close_total 5415
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 651
telemt_me_draining_writers_reap_progress_total 61586
telemt_me_writer_removed_unexpected_total 2667
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6483
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57801
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4666
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56171
telemt_me_writer_teardown_success_total{mode="normal"} 64284
telemt_me_writer_teardown_noop_total 61587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125871
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.156984
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125871
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 651
telemt_me_refill_failed_total 4291
telemt_me_writer_restored_same_endpoint_total 2482
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 8587751
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 193697490037 (180.39 GB)
telemt_user_octets_to_client{user="hello"} 3279219800788 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 115116.3 (31h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11520663
telemt_connections_bad_total 459803
telemt_connections_current 803
telemt_connections_me_current 803
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4724975
telemt_upstream_connect_attempt_total 54457
telemt_upstream_connect_success_total 54053
telemt_upstream_connect_fail_total 393
telemt_upstream_connect_attempts_per_request{bucket="1"} 54446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 393
telemt_me_reconnect_attempts_total 48680
telemt_me_reconnect_success_total 1719
telemt_me_reader_eof_total 1383
telemt_me_idle_close_by_peer_total 1382
telemt_me_route_drop_no_conn_total 4069968
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5544807
telemt_me_endpoint_quarantine_total 747
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 871
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31169
telemt_desync_full_logged_total 10618
telemt_desync_suppressed_total 20551
telemt_desync_frames_bucket_total{bucket="1_2"} 6186
telemt_desync_frames_bucket_total{bucket="3_10"} 12309
telemt_desync_frames_bucket_total{bucket="gt_10"} 12674
telemt_pool_swap_total 121
telemt_pool_force_close_total 3663
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 365
telemt_me_draining_writers_reap_progress_total 40521
telemt_me_writer_removed_unexpected_total 1437
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3496
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38502
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3222
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36858
telemt_me_writer_teardown_success_total{mode="normal"} 41998
telemt_me_writer_teardown_noop_total 40528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82526
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.628363
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82526
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 365
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1524
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5537447
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 118370723252 (110.24 GB)
telemt_user_octets_to_client{user="hello"} 2129266271230 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 96087.0 (26h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1447857
telemt_connections_bad_total 36329
telemt_connections_current 637
telemt_connections_me_current 637
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 28668
telemt_upstream_connect_attempt_total 44963
telemt_upstream_connect_success_total 44822
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 44935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 761
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2066
telemt_me_reconnect_success_total 851
telemt_me_reader_eof_total 832
telemt_me_idle_close_by_peer_total 832
telemt_me_route_drop_no_conn_total 500860
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1284108
telemt_me_endpoint_quarantine_total 773
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 790
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 44
telemt_desync_total 8031
telemt_desync_full_logged_total 2438
telemt_desync_suppressed_total 5593
telemt_desync_frames_bucket_total{bucket="1_2"} 1966
telemt_desync_frames_bucket_total{bucket="3_10"} 3106
telemt_desync_frames_bucket_total{bucket="gt_10"} 2959
telemt_pool_swap_total 103
telemt_pool_force_close_total 2685
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 149
telemt_me_draining_writers_reap_progress_total 37641
telemt_me_writer_removed_unexpected_total 801
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2961
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35515
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2597
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34956
telemt_me_writer_teardown_success_total{mode="normal"} 38476
telemt_me_writer_teardown_noop_total 37645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76121
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.959419
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76121
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 149
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 721
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 1280040
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 25185489513 (23.46 GB)
telemt_user_octets_to_client{user="hello"} 543380102591 (506.06 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 178284.5 (49h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13196143
telemt_connections_bad_total 1565252
telemt_connections_current 971
telemt_connections_me_current 971
telemt_handshake_timeouts_total 379105
telemt_upstream_connect_attempt_total 68112
telemt_upstream_connect_success_total 67774
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 67976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2649
telemt_me_reconnect_success_total 1387
telemt_me_reader_eof_total 1355
telemt_me_idle_close_by_peer_total 1355
telemt_me_route_drop_no_conn_total 4467918
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9973845
telemt_me_endpoint_quarantine_total 1213
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1335
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 32
telemt_desync_total 41684
telemt_desync_full_logged_total 13600
telemt_desync_suppressed_total 28084
telemt_desync_frames_bucket_total{bucket="1_2"} 10014
telemt_desync_frames_bucket_total{bucket="3_10"} 15342
telemt_desync_frames_bucket_total{bucket="gt_10"} 16328
telemt_pool_swap_total 197
telemt_pool_force_close_total 5380
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 660
telemt_me_draining_writers_reap_progress_total 61396
telemt_me_writer_removed_unexpected_total 1304
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4962
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57779
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5206
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56016
telemt_me_writer_teardown_success_total{mode="normal"} 62741
telemt_me_writer_teardown_noop_total 61398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124139
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.577182
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124139
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 660
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1214
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 9940660
telemt_user_connections_current{user="hello"} 971
telemt_user_octets_from_client{user="hello"} 194023276180 (180.70 GB)
telemt_user_octets_to_client{user="hello"} 4403294641016 (4.00 TB)
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 178281.2 (49h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11484743
telemt_connections_bad_total 1308059
telemt_connections_current 899
telemt_connections_me_current 899
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 303682
telemt_upstream_connect_attempt_total 94608
telemt_upstream_connect_success_total 93760
telemt_upstream_connect_fail_total 641
telemt_upstream_connect_attempts_per_request{bucket="1"} 94401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2066
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 641
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10089
telemt_me_reconnect_success_total 2440
telemt_me_reader_eof_total 2277
telemt_me_idle_close_by_peer_total 2276
telemt_me_seq_mismatch_total 85
telemt_me_route_drop_no_conn_total 5627326
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8874025
telemt_me_endpoint_quarantine_total 1375
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1337
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 30
telemt_desync_total 41267
telemt_desync_full_logged_total 13241
telemt_desync_suppressed_total 28026
telemt_desync_frames_bucket_total{bucket="1_2"} 10593
telemt_desync_frames_bucket_total{bucket="3_10"} 15191
telemt_desync_frames_bucket_total{bucket="gt_10"} 15483
telemt_pool_swap_total 187
telemt_pool_force_close_total 5172
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 649
telemt_me_draining_writers_reap_progress_total 61194
telemt_me_writer_removed_unexpected_total 2311
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6298
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57287
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4701
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56022
telemt_me_writer_teardown_success_total{mode="normal"} 63585
telemt_me_writer_teardown_noop_total 61199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124784
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.306098
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124784
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 649
telemt_me_refill_failed_total 395
telemt_me_writer_restored_same_endpoint_total 1978
telemt_me_writer_restored_fallback_total 117
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 8879467
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 156693516673 (145.93 GB)
telemt_user_octets_to_client{user="hello"} 3456356774767 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 87
```