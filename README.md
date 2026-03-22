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

# Server Metrics 2026-03-22 15:43:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 67041.5 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2347207
telemt_connections_bad_total 126133
telemt_connections_current 1632
telemt_connections_me_current 1632
telemt_handshake_timeouts_total 86170
telemt_upstream_connect_attempt_total 24833
telemt_upstream_connect_success_total 24832
telemt_upstream_connect_attempts_per_request{bucket="1"} 24832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1019
telemt_me_reconnect_success_total 427
telemt_me_reader_eof_total 429
telemt_me_idle_close_by_peer_total 429
telemt_me_route_drop_no_conn_total 1904319
telemt_me_route_drop_channel_closed_total 764
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1994238
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 527
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 9837
telemt_desync_full_logged_total 3042
telemt_desync_suppressed_total 6795
telemt_desync_frames_bucket_total{bucket="1_2"} 2649
telemt_desync_frames_bucket_total{bucket="3_10"} 3684
telemt_desync_frames_bucket_total{bucket="gt_10"} 3504
telemt_pool_swap_total 74
telemt_pool_force_close_total 2276
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 428
telemt_me_draining_writers_reap_progress_total 22661
telemt_me_writer_removed_unexpected_total 416
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1651
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21225
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2229
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20385
telemt_me_writer_teardown_success_total{mode="normal"} 22876
telemt_me_writer_teardown_noop_total 22667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45543
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 203.569232
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45543
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 428
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1990906
telemt_user_connections_current{user="hello"} 1632
telemt_user_octets_from_client{user="hello"} 30212646336 (28.14 GB)
telemt_user_octets_to_client{user="hello"} 533627891228 (496.98 GB)
telemt_user_unique_ips_current{user="hello"} 631
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 80408.0 (22h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3545013
telemt_connections_bad_total 322224
telemt_connections_current 1356
telemt_connections_me_current 1356
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 85344
telemt_upstream_connect_attempt_total 50885
telemt_upstream_connect_success_total 50261
telemt_upstream_connect_fail_total 552
telemt_upstream_connect_attempts_per_request{bucket="1"} 50813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 552
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5839
telemt_me_reconnect_success_total 2073
telemt_me_reader_eof_total 2008
telemt_me_idle_close_by_peer_total 2008
telemt_me_route_drop_no_conn_total 3515816
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2809114
telemt_me_endpoint_quarantine_total 644
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 621
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_me_writers_active_current 128
telemt_desync_total 10883
telemt_desync_full_logged_total 6049
telemt_desync_suppressed_total 4834
telemt_desync_frames_bucket_total{bucket="1_2"} 2552
telemt_desync_frames_bucket_total{bucket="3_10"} 4289
telemt_desync_frames_bucket_total{bucket="gt_10"} 4042
telemt_pool_swap_total 75
telemt_pool_force_close_total 2228
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 31938
telemt_me_writer_removed_unexpected_total 1962
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3784
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30121
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 318
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29710
telemt_me_writer_teardown_success_total{mode="normal"} 33905
telemt_me_writer_teardown_noop_total 31938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65843
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.590109
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65843
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 147
telemt_me_writer_restored_same_endpoint_total 1783
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 2820471
telemt_user_connections_current{user="hello"} 1356
telemt_user_octets_from_client{user="hello"} 34533905791 (32.16 GB)
telemt_user_octets_to_client{user="hello"} 618292541478 (575.83 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 788
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 155267.9 (43h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15175407
telemt_connections_bad_total 1392176
telemt_connections_current 2049
telemt_connections_me_current 2049
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 368875
telemt_upstream_connect_attempt_total 70392
telemt_upstream_connect_success_total 70297
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 70314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1668
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2588
telemt_me_reconnect_success_total 1336
telemt_me_reader_eof_total 1274
telemt_me_idle_close_by_peer_total 1272
telemt_me_route_drop_no_conn_total 13767794
telemt_me_route_drop_channel_closed_total 137
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12144859
telemt_me_endpoint_quarantine_total 981
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1157
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 49179
telemt_desync_full_logged_total 15435
telemt_desync_suppressed_total 33744
telemt_desync_frames_bucket_total{bucket="1_2"} 11042
telemt_desync_frames_bucket_total{bucket="3_10"} 19230
telemt_desync_frames_bucket_total{bucket="gt_10"} 18907
telemt_pool_swap_total 167
telemt_pool_force_close_total 5691
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 930
telemt_me_draining_writers_reap_progress_total 51087
telemt_me_writer_removed_unexpected_total 1229
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4446
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47176
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5231
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45396
telemt_me_writer_teardown_success_total{mode="normal"} 51622
telemt_me_writer_teardown_noop_total 51137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102759
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 292.892853
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102759
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 930
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 1146
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 12146160
telemt_user_connections_current{user="hello"} 2049
telemt_user_octets_from_client{user="hello"} 170927915001 (159.19 GB)
telemt_user_octets_to_client{user="hello"} 3125409553187 (2.84 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 818
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 155269.3 (43h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10951570
telemt_connections_bad_total 1058403
telemt_connections_current 1549
telemt_connections_me_current 1549
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 324481
telemt_upstream_connect_attempt_total 82571
telemt_upstream_connect_success_total 81419
telemt_upstream_connect_fail_total 828
telemt_upstream_connect_attempts_per_request{bucket="1"} 82247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 828
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3899
telemt_me_reconnect_success_total 1582
telemt_me_reader_eof_total 1449
telemt_me_idle_close_by_peer_total 1449
telemt_me_route_drop_no_conn_total 4335523
telemt_me_route_drop_channel_closed_total 477
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8172488
telemt_me_endpoint_quarantine_total 977
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1177
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 36276
telemt_desync_full_logged_total 12183
telemt_desync_suppressed_total 24093
telemt_desync_frames_bucket_total{bucket="1_2"} 8897
telemt_desync_frames_bucket_total{bucket="3_10"} 13967
telemt_desync_frames_bucket_total{bucket="gt_10"} 13412
telemt_pool_swap_total 165
telemt_pool_force_close_total 5126
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 49369
telemt_me_writer_removed_unexpected_total 1481
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4558
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46149
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4652
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 474
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44243
telemt_me_writer_teardown_success_total{mode="normal"} 50707
telemt_me_writer_teardown_noop_total 49387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100094
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.178751
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100094
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 125
telemt_me_writer_restored_same_endpoint_total 1344
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 8111292
telemt_user_connections_current{user="hello"} 1549
telemt_user_octets_from_client{user="hello"} 203485397637 (189.51 GB)
telemt_user_octets_to_client{user="hello"} 3656773220422 (3.33 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 605
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 155233.4 (43h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10373784
telemt_connections_bad_total 891121
telemt_connections_current 1234
telemt_connections_me_current 1234
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 330505
telemt_upstream_connect_attempt_total 67796
telemt_upstream_connect_success_total 66869
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 67051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4621
telemt_me_reconnect_success_total 1863
telemt_me_reader_eof_total 1620
telemt_me_idle_close_by_peer_total 1619
telemt_me_route_drop_no_conn_total 5106449
telemt_me_route_drop_channel_closed_total 355
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7832225
telemt_me_endpoint_quarantine_total 1065
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 1142
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
telemt_desync_total 35858
telemt_desync_full_logged_total 11880
telemt_desync_suppressed_total 23978
telemt_desync_frames_bucket_total{bucket="1_2"} 9069
telemt_desync_frames_bucket_total{bucket="3_10"} 13709
telemt_desync_frames_bucket_total{bucket="gt_10"} 13080
telemt_pool_swap_total 162
telemt_pool_force_close_total 5075
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 683
telemt_me_draining_writers_reap_progress_total 49834
telemt_me_writer_removed_unexpected_total 1760
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46516
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4538
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 537
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44759
telemt_me_writer_teardown_success_total{mode="normal"} 51506
telemt_me_writer_teardown_noop_total 49905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101411
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3170.148291
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101411
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 683
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1614
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 7825283
telemt_user_connections_current{user="hello"} 1234
telemt_user_octets_from_client{user="hello"} 180740817101 (168.33 GB)
telemt_user_octets_to_client{user="hello"} 3251809863961 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 25512.7 (7h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10002313
telemt_connections_bad_total 611234
telemt_connections_current 2297
telemt_connections_me_current 2297
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 171977
telemt_upstream_connect_attempt_total 34817
telemt_upstream_connect_success_total 33070
telemt_upstream_connect_fail_total 1247
telemt_upstream_connect_attempts_per_request{bucket="1"} 34317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8771
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1247
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5785
telemt_me_reconnect_success_total 676
telemt_me_reader_eof_total 421
telemt_me_idle_close_by_peer_total 421
telemt_me_route_drop_no_conn_total 24851460
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8336154
telemt_me_endpoint_quarantine_total 164
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 82
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 82
telemt_me_single_endpoint_shadow_rotate_total 201
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 12738
telemt_desync_full_logged_total 3255
telemt_desync_suppressed_total 9483
telemt_desync_frames_bucket_total{bucket="1_2"} 2208
telemt_desync_frames_bucket_total{bucket="3_10"} 5185
telemt_desync_frames_bucket_total{bucket="gt_10"} 5345
telemt_pool_swap_total 24
telemt_pool_force_close_total 982
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 6897
telemt_me_writer_removed_unexpected_total 583
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1179
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6265
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5915
telemt_me_writer_teardown_success_total{mode="normal"} 7444
telemt_me_writer_teardown_noop_total 6902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14346
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 34.994764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14346
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 459
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 8354423
telemt_user_connections_current{user="hello"} 2297
telemt_user_octets_from_client{user="hello"} 56288051054 (52.42 GB)
telemt_user_octets_to_client{user="hello"} 266611070756 (248.30 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 829
telemt_user_unique_ips_recent_window{user="hello"} 326
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 155239.6 (43h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10132741
telemt_connections_bad_total 844100
telemt_connections_current 1939
telemt_connections_me_current 1939
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 223116
telemt_upstream_connect_attempt_total 96500
telemt_upstream_connect_success_total 95523
telemt_upstream_connect_fail_total 833
telemt_upstream_connect_attempts_per_request{bucket="1"} 96356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34771
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1298
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 833
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71692
telemt_me_reconnect_success_total 2582
telemt_me_reader_eof_total 2286
telemt_me_idle_close_by_peer_total 2285
telemt_me_route_drop_no_conn_total 5033334
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7996664
telemt_me_endpoint_quarantine_total 1050
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1159
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
telemt_me_writers_active_current 46
telemt_desync_total 41556
telemt_desync_full_logged_total 14187
telemt_desync_suppressed_total 27369
telemt_desync_frames_bucket_total{bucket="1_2"} 8466
telemt_desync_frames_bucket_total{bucket="3_10"} 16091
telemt_desync_frames_bucket_total{bucket="gt_10"} 16999
telemt_pool_swap_total 158
telemt_pool_force_close_total 4707
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 591
telemt_me_draining_writers_reap_progress_total 52892
telemt_me_writer_removed_unexpected_total 2330
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5665
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49577
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 682
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48185
telemt_me_writer_teardown_success_total{mode="normal"} 55242
telemt_me_writer_teardown_noop_total 52893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108135
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.351723
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108135
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 591
telemt_me_refill_failed_total 4262
telemt_me_writer_restored_same_endpoint_total 2170
telemt_me_writer_restored_fallback_total 44
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7360
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 8000706
telemt_user_connections_current{user="hello"} 1939
telemt_user_octets_from_client{user="hello"} 181194395873 (168.75 GB)
telemt_user_octets_to_client{user="hello"} 3006191440564 (2.73 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 668
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 92075.6 (25h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10534005
telemt_connections_bad_total 388288
telemt_connections_current 1357
telemt_connections_me_current 1357
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4446636
telemt_upstream_connect_attempt_total 44513
telemt_upstream_connect_success_total 44186
telemt_upstream_connect_fail_total 317
telemt_upstream_connect_attempts_per_request{bucket="1"} 44503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 317
telemt_me_reconnect_attempts_total 48034
telemt_me_reconnect_success_total 1498
telemt_me_reader_eof_total 1161
telemt_me_idle_close_by_peer_total 1160
telemt_me_route_drop_no_conn_total 3891288
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5043753
telemt_me_endpoint_quarantine_total 603
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 694
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 27529
telemt_desync_full_logged_total 9292
telemt_desync_suppressed_total 18237
telemt_desync_frames_bucket_total{bucket="1_2"} 5552
telemt_desync_frames_bucket_total{bucket="3_10"} 10878
telemt_desync_frames_bucket_total{bucket="gt_10"} 11099
telemt_pool_swap_total 97
telemt_pool_force_close_total 3006
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 310
telemt_me_draining_writers_reap_progress_total 31623
telemt_me_writer_removed_unexpected_total 1224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2857
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30020
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2587
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28617
telemt_me_writer_teardown_success_total{mode="normal"} 32877
telemt_me_writer_teardown_noop_total 31630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64507
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.663217
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64507
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 310
telemt_me_refill_failed_total 2705
telemt_me_writer_restored_same_endpoint_total 1332
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5037389
telemt_user_connections_current{user="hello"} 1357
telemt_user_octets_from_client{user="hello"} 108665507400 (101.20 GB)
telemt_user_octets_to_client{user="hello"} 1898276726478 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 73046.3 (20h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 950249
telemt_connections_bad_total 13274
telemt_connections_current 1116
telemt_connections_me_current 1116
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18478
telemt_upstream_connect_attempt_total 36142
telemt_upstream_connect_success_total 36051
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 36126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_reconnect_attempts_total 1620
telemt_me_reconnect_success_total 689
telemt_me_reader_eof_total 664
telemt_me_idle_close_by_peer_total 664
telemt_me_route_drop_no_conn_total 326671
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 844252
telemt_me_endpoint_quarantine_total 637
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 605
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 4695
telemt_desync_full_logged_total 1430
telemt_desync_suppressed_total 3265
telemt_desync_frames_bucket_total{bucket="1_2"} 1098
telemt_desync_frames_bucket_total{bucket="3_10"} 1865
telemt_desync_frames_bucket_total{bucket="gt_10"} 1732
telemt_pool_swap_total 78
telemt_pool_force_close_total 1938
telemt_me_writer_close_signal_drop_total 111
telemt_me_draining_writers_reap_progress_total 29859
telemt_me_writer_removed_unexpected_total 641
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2305
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28220
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1860
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27921
telemt_me_writer_teardown_success_total{mode="normal"} 30525
telemt_me_writer_teardown_noop_total 29861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60386
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.479756
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60386
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 111
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 587
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 845303
telemt_user_connections_current{user="hello"} 1116
telemt_user_octets_from_client{user="hello"} 15347234585 (14.29 GB)
telemt_user_octets_to_client{user="hello"} 381775277459 (355.56 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 155244.4 (43h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12411545
telemt_connections_bad_total 1441753
telemt_connections_current 1941
telemt_connections_me_current 1941
telemt_handshake_timeouts_total 340271
telemt_upstream_connect_attempt_total 58173
telemt_upstream_connect_success_total 57946
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 58123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_reconnect_attempts_total 2262
telemt_me_reconnect_success_total 1206
telemt_me_reader_eof_total 1170
telemt_me_idle_close_by_peer_total 1170
telemt_me_route_drop_no_conn_total 4142396
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9378494
telemt_me_endpoint_quarantine_total 1051
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1160
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 38435
telemt_desync_full_logged_total 12555
telemt_desync_suppressed_total 25880
telemt_desync_frames_bucket_total{bucket="1_2"} 9132
telemt_desync_frames_bucket_total{bucket="3_10"} 14242
telemt_desync_frames_bucket_total{bucket="gt_10"} 15061
telemt_pool_swap_total 172
telemt_pool_force_close_total 4758
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 52405
telemt_me_writer_removed_unexpected_total 1124
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4301
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49260
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4585
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47647
telemt_me_writer_teardown_success_total{mode="normal"} 53561
telemt_me_writer_teardown_noop_total 52407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105968
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.942746
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105968
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1055
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9347843
telemt_user_connections_current{user="hello"} 1941
telemt_user_octets_from_client{user="hello"} 182202611524 (169.69 GB)
telemt_user_octets_to_client{user="hello"} 4130933252040 (3.76 TB)
telemt_user_unique_ips_current{user="hello"} 668
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 155240.8 (43h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10754556
telemt_connections_bad_total 1200895
telemt_connections_current 1515
telemt_connections_me_current 1515
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 277588
telemt_upstream_connect_attempt_total 83969
telemt_upstream_connect_success_total 83342
telemt_upstream_connect_fail_total 543
telemt_upstream_connect_attempts_per_request{bucket="1"} 83885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2028
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 543
telemt_me_reconnect_attempts_total 8871
telemt_me_reconnect_success_total 2034
telemt_me_reader_eof_total 1899
telemt_me_idle_close_by_peer_total 1899
telemt_me_seq_mismatch_total 74
telemt_me_route_drop_no_conn_total 5390716
telemt_me_route_drop_channel_closed_total 344
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8312250
telemt_me_endpoint_quarantine_total 1179
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1163
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 38017
telemt_desync_full_logged_total 12284
telemt_desync_suppressed_total 25733
telemt_desync_frames_bucket_total{bucket="1_2"} 9457
telemt_desync_frames_bucket_total{bucket="3_10"} 14169
telemt_desync_frames_bucket_total{bucket="gt_10"} 14391
telemt_pool_swap_total 164
telemt_pool_force_close_total 4603
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 599
telemt_me_draining_writers_reap_progress_total 51874
telemt_me_writer_removed_unexpected_total 1926
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5397
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48470
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47271
telemt_me_writer_teardown_success_total{mode="normal"} 53867
telemt_me_writer_teardown_noop_total 51879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105746
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.451808
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105746
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 599
telemt_me_refill_failed_total 351
telemt_me_writer_restored_same_endpoint_total 1654
telemt_me_writer_restored_fallback_total 99
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 8318301
telemt_user_connections_current{user="hello"} 1515
telemt_user_octets_from_client{user="hello"} 146511242889 (136.45 GB)
telemt_user_octets_to_client{user="hello"} 3174517627191 (2.89 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 185
```