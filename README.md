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

# Server Metrics 2026-03-22 18:58:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 78718.1 (21h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2913710
telemt_connections_bad_total 183846
telemt_connections_current 1204
telemt_connections_me_current 1204
telemt_handshake_timeouts_total 97289
telemt_upstream_connect_attempt_total 28776
telemt_upstream_connect_success_total 28775
telemt_upstream_connect_attempts_per_request{bucket="1"} 28775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1173
telemt_me_reconnect_success_total 489
telemt_me_reader_eof_total 492
telemt_me_idle_close_by_peer_total 492
telemt_me_route_drop_no_conn_total 2535873
telemt_me_route_drop_channel_closed_total 1020
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2471344
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 529
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 612
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 10887
telemt_desync_full_logged_total 3456
telemt_desync_suppressed_total 7431
telemt_desync_frames_bucket_total{bucket="1_2"} 2923
telemt_desync_frames_bucket_total{bucket="3_10"} 4041
telemt_desync_frames_bucket_total{bucket="gt_10"} 3923
telemt_pool_swap_total 87
telemt_pool_force_close_total 2709
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 554
telemt_me_draining_writers_reap_progress_total 26308
telemt_me_writer_removed_unexpected_total 478
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1915
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24613
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2656
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23599
telemt_me_writer_teardown_success_total{mode="normal"} 26528
telemt_me_writer_teardown_noop_total 26318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52846
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 283.781010
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52846
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 554
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 431
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2466821
telemt_user_connections_current{user="hello"} 1204
telemt_user_octets_from_client{user="hello"} 35531545064 (33.09 GB)
telemt_user_octets_to_client{user="hello"} 646608100664 (602.20 GB)
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 92083.8 (25h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3776998
telemt_connections_bad_total 338593
telemt_connections_current 603
telemt_connections_me_current 603
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 96485
telemt_upstream_connect_attempt_total 56160
telemt_upstream_connect_success_total 55471
telemt_upstream_connect_fail_total 607
telemt_upstream_connect_attempts_per_request{bucket="1"} 56078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 607
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6383
telemt_me_reconnect_success_total 2341
telemt_me_reader_eof_total 2275
telemt_me_idle_close_by_peer_total 2275
telemt_me_route_drop_no_conn_total 3587934
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3001808
telemt_me_endpoint_quarantine_total 720
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 711
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 11939
telemt_desync_full_logged_total 6679
telemt_desync_suppressed_total 5260
telemt_desync_frames_bucket_total{bucket="1_2"} 2746
telemt_desync_frames_bucket_total{bucket="3_10"} 4670
telemt_desync_frames_bucket_total{bucket="gt_10"} 4523
telemt_pool_swap_total 87
telemt_pool_force_close_total 2630
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 36608
telemt_me_writer_removed_unexpected_total 2225
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4330
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34515
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2241
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33978
telemt_me_writer_teardown_success_total{mode="normal"} 38845
telemt_me_writer_teardown_noop_total 36608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75453
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.853941
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75453
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 161
telemt_me_writer_restored_same_endpoint_total 2028
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 3012618
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 39013059503 (36.33 GB)
telemt_user_octets_to_client{user="hello"} 704306319342 (655.94 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 166943.7 (46h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15793903
telemt_connections_bad_total 1521762
telemt_connections_current 2201
telemt_connections_me_current 2201
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 390143
telemt_upstream_connect_attempt_total 74510
telemt_upstream_connect_success_total 74413
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 74430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35552
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2766
telemt_me_reconnect_success_total 1421
telemt_me_reader_eof_total 1362
telemt_me_idle_close_by_peer_total 1360
telemt_me_route_drop_no_conn_total 13929330
telemt_me_route_drop_channel_closed_total 142
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12584468
telemt_me_endpoint_quarantine_total 1055
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1245
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 51920
telemt_desync_full_logged_total 16320
telemt_desync_suppressed_total 35600
telemt_desync_frames_bucket_total{bucket="1_2"} 11588
telemt_desync_frames_bucket_total{bucket="3_10"} 20225
telemt_desync_frames_bucket_total{bucket="gt_10"} 20107
telemt_pool_swap_total 180
telemt_pool_force_close_total 6089
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 988
telemt_me_draining_writers_reap_progress_total 54810
telemt_me_writer_removed_unexpected_total 1314
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4807
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50610
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5621
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48721
telemt_me_writer_teardown_success_total{mode="normal"} 55417
telemt_me_writer_teardown_noop_total 54860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110277
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 308.051229
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110277
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 988
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1225
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12585086
telemt_user_connections_current{user="hello"} 2201
telemt_user_octets_from_client{user="hello"} 183373508017 (170.78 GB)
telemt_user_octets_to_client{user="hello"} 3310051285571 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 844
telemt_user_unique_ips_recent_window{user="hello"} 253
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 166945.1 (46h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11399967
telemt_connections_bad_total 1126480
telemt_connections_current 1593
telemt_connections_me_current 1593
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 340027
telemt_upstream_connect_attempt_total 87026
telemt_upstream_connect_success_total 85816
telemt_upstream_connect_fail_total 842
telemt_upstream_connect_attempts_per_request{bucket="1"} 86658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35494
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3706
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 842
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4099
telemt_me_reconnect_success_total 1694
telemt_me_reader_eof_total 1562
telemt_me_idle_close_by_peer_total 1562
telemt_me_route_drop_no_conn_total 4458348
telemt_me_route_drop_channel_closed_total 490
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8495032
telemt_me_endpoint_quarantine_total 1057
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1265
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
telemt_me_writers_active_current 44
telemt_desync_total 37691
telemt_desync_full_logged_total 12701
telemt_desync_suppressed_total 24990
telemt_desync_frames_bucket_total{bucket="1_2"} 9293
telemt_desync_frames_bucket_total{bucket="3_10"} 14518
telemt_desync_frames_bucket_total{bucket="gt_10"} 13880
telemt_pool_swap_total 177
telemt_pool_force_close_total 5498
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 696
telemt_me_draining_writers_reap_progress_total 53299
telemt_me_writer_removed_unexpected_total 1601
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4922
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49822
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4997
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 501
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47801
telemt_me_writer_teardown_success_total{mode="normal"} 54744
telemt_me_writer_teardown_noop_total 53322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108066
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.190765
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108066
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 696
telemt_me_refill_failed_total 130
telemt_me_writer_restored_same_endpoint_total 1450
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 8433393
telemt_user_connections_current{user="hello"} 1593
telemt_user_octets_from_client{user="hello"} 210667838505 (196.20 GB)
telemt_user_octets_to_client{user="hello"} 3802424698814 (3.46 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 584
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 166912.0 (46h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10724750
telemt_connections_bad_total 923915
telemt_connections_current 1344
telemt_connections_me_current 1344
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 342634
telemt_upstream_connect_attempt_total 72115
telemt_upstream_connect_success_total 71054
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 71238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33928
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4905
telemt_me_reconnect_success_total 1983
telemt_me_reader_eof_total 1732
telemt_me_idle_close_by_peer_total 1731
telemt_me_route_drop_no_conn_total 5228589
telemt_me_route_drop_channel_closed_total 371
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8104529
telemt_me_endpoint_quarantine_total 1140
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1226
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 59
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
telemt_desync_total 37226
telemt_desync_full_logged_total 12313
telemt_desync_suppressed_total 24913
telemt_desync_frames_bucket_total{bucket="1_2"} 9421
telemt_desync_frames_bucket_total{bucket="3_10"} 14260
telemt_desync_frames_bucket_total{bucket="gt_10"} 13545
telemt_pool_swap_total 175
telemt_pool_force_close_total 5436
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 702
telemt_me_draining_writers_reap_progress_total 53447
telemt_me_writer_removed_unexpected_total 1873
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5370
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49867
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4890
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 546
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48011
telemt_me_writer_teardown_success_total{mode="normal"} 55237
telemt_me_writer_teardown_noop_total 53518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108755
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.642623
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108755
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 702
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 1709
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 8096971
telemt_user_connections_current{user="hello"} 1344
telemt_user_octets_from_client{user="hello"} 187506405269 (174.63 GB)
telemt_user_octets_to_client{user="hello"} 3371590699949 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 500
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 37189.0 (10h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10647032
telemt_connections_bad_total 651024
telemt_connections_current 2059
telemt_connections_me_current 2059
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 222186
telemt_upstream_connect_attempt_total 43942
telemt_upstream_connect_success_total 41725
telemt_upstream_connect_fail_total 1538
telemt_upstream_connect_attempts_per_request{bucket="1"} 43263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12924
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5951
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1538
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6392
telemt_me_reconnect_success_total 862
telemt_me_reader_eof_total 530
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 25137651
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8841621
telemt_me_endpoint_quarantine_total 235
telemt_me_single_endpoint_outage_enter_total 63
telemt_me_single_endpoint_outage_exit_total 63
telemt_me_single_endpoint_outage_reconnect_attempt_total 114
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 114
telemt_me_single_endpoint_shadow_rotate_total 293
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 14202
telemt_desync_full_logged_total 3710
telemt_desync_suppressed_total 10492
telemt_desync_frames_bucket_total{bucket="1_2"} 2623
telemt_desync_frames_bucket_total{bucket="3_10"} 5750
telemt_desync_frames_bucket_total{bucket="gt_10"} 5829
telemt_pool_swap_total 37
telemt_pool_force_close_total 1372
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 416
telemt_me_draining_writers_reap_progress_total 10553
telemt_me_writer_removed_unexpected_total 775
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1619
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9668
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1083
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 289
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9181
telemt_me_writer_teardown_success_total{mode="normal"} 11287
telemt_me_writer_teardown_noop_total 10572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21859
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.853782
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21859
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 416
telemt_me_refill_failed_total 306
telemt_me_writer_restored_same_endpoint_total 573
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 8863886
telemt_user_connections_current{user="hello"} 2059
telemt_user_octets_from_client{user="hello"} 80703382107 (75.16 GB)
telemt_user_octets_to_client{user="hello"} 436026119419 (406.08 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 737
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 166915.5 (46h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10579910
telemt_connections_bad_total 891074
telemt_connections_current 1775
telemt_connections_me_current 1775
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 233202
telemt_upstream_connect_attempt_total 101119
telemt_upstream_connect_success_total 100051
telemt_upstream_connect_fail_total 909
telemt_upstream_connect_attempts_per_request{bucket="1"} 100960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1329
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 909
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72233
telemt_me_reconnect_success_total 2745
telemt_me_reader_eof_total 2433
telemt_me_idle_close_by_peer_total 2431
telemt_me_route_drop_no_conn_total 5160156
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8353643
telemt_me_endpoint_quarantine_total 1110
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1248
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 44409
telemt_desync_full_logged_total 15122
telemt_desync_suppressed_total 29287
telemt_desync_frames_bucket_total{bucket="1_2"} 9005
telemt_desync_frames_bucket_total{bucket="3_10"} 17053
telemt_desync_frames_bucket_total{bucket="gt_10"} 18351
telemt_pool_swap_total 171
telemt_pool_force_close_total 5090
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 627
telemt_me_draining_writers_reap_progress_total 56872
telemt_me_writer_removed_unexpected_total 2472
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6054
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53315
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4393
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 697
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51782
telemt_me_writer_teardown_success_total{mode="normal"} 59369
telemt_me_writer_teardown_noop_total 56873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116242
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.918420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116242
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 627
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2298
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8357113
telemt_user_connections_current{user="hello"} 1775
telemt_user_octets_from_client{user="hello"} 189759801233 (176.73 GB)
telemt_user_octets_to_client{user="hello"} 3171171555704 (2.88 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 694
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 103751.7 (28h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11121946
telemt_connections_bad_total 432770
telemt_connections_current 1441
telemt_connections_me_current 1441
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4605520
telemt_upstream_connect_attempt_total 49396
telemt_upstream_connect_success_total 49030
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 49387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_reconnect_attempts_total 48302
telemt_me_reconnect_success_total 1634
telemt_me_reader_eof_total 1293
telemt_me_idle_close_by_peer_total 1292
telemt_me_route_drop_no_conn_total 4006407
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5349392
telemt_me_endpoint_quarantine_total 674
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 784
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29929
telemt_desync_full_logged_total 10122
telemt_desync_suppressed_total 19807
telemt_desync_frames_bucket_total{bucket="1_2"} 6002
telemt_desync_frames_bucket_total{bucket="3_10"} 11825
telemt_desync_frames_bucket_total{bucket="gt_10"} 12102
telemt_pool_swap_total 109
telemt_pool_force_close_total 3348
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 35973
telemt_me_writer_removed_unexpected_total 1354
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3221
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34139
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2909
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32625
telemt_me_writer_teardown_success_total{mode="normal"} 37360
telemt_me_writer_teardown_noop_total 35980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73340
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.324935
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73340
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1458
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5342369
telemt_user_connections_current{user="hello"} 1441
telemt_user_octets_from_client{user="hello"} 115076113368 (107.17 GB)
telemt_user_octets_to_client{user="hello"} 2039050857482 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 539
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 84722.9 (23h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1247929
telemt_connections_bad_total 27279
telemt_connections_current 1137
telemt_connections_me_current 1137
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24047
telemt_upstream_connect_attempt_total 40527
telemt_upstream_connect_success_total 40406
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 40500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 666
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1843
telemt_me_reconnect_success_total 782
telemt_me_reader_eof_total 755
telemt_me_idle_close_by_peer_total 755
telemt_me_route_drop_no_conn_total 435689
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1105632
telemt_me_endpoint_quarantine_total 713
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 695
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
telemt_me_writers_active_current 42
telemt_desync_total 6409
telemt_desync_full_logged_total 1982
telemt_desync_suppressed_total 4427
telemt_desync_frames_bucket_total{bucket="1_2"} 1455
telemt_desync_frames_bucket_total{bucket="3_10"} 2522
telemt_desync_frames_bucket_total{bucket="gt_10"} 2432
telemt_pool_swap_total 91
telemt_pool_force_close_total 2321
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 33659
telemt_me_writer_removed_unexpected_total 729
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2636
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31781
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2236
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31338
telemt_me_writer_teardown_success_total{mode="normal"} 34417
telemt_me_writer_teardown_noop_total 33663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68080
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.081460
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68080
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 661
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1101889
telemt_user_connections_current{user="hello"} 1137
telemt_user_octets_from_client{user="hello"} 20926019325 (19.49 GB)
telemt_user_octets_to_client{user="hello"} 468235962951 (436.08 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 166920.1 (46h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12893940
telemt_connections_bad_total 1506508
telemt_connections_current 1645
telemt_connections_me_current 1645
telemt_handshake_timeouts_total 365831
telemt_upstream_connect_attempt_total 62869
telemt_upstream_connect_success_total 62540
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 62734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31557
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2454
telemt_me_reconnect_success_total 1298
telemt_me_reader_eof_total 1261
telemt_me_idle_close_by_peer_total 1261
telemt_me_route_drop_no_conn_total 4386257
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9752981
telemt_me_endpoint_quarantine_total 1116
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1249
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 40109
telemt_desync_full_logged_total 13078
telemt_desync_suppressed_total 27031
telemt_desync_frames_bucket_total{bucket="1_2"} 9576
telemt_desync_frames_bucket_total{bucket="3_10"} 14809
telemt_desync_frames_bucket_total{bucket="gt_10"} 15724
telemt_pool_swap_total 185
telemt_pool_force_close_total 5098
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 643
telemt_me_draining_writers_reap_progress_total 56613
telemt_me_writer_removed_unexpected_total 1213
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4649
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53215
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4924
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51515
telemt_me_writer_teardown_success_total{mode="normal"} 57864
telemt_me_writer_teardown_noop_total 56615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114479
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.107292
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114479
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 643
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 1135
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 9720885
telemt_user_connections_current{user="hello"} 1645
telemt_user_octets_from_client{user="hello"} 190243445396 (177.18 GB)
telemt_user_octets_to_client{user="hello"} 4287752952276 (3.90 TB)
telemt_user_unique_ips_current{user="hello"} 597
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 166916.8 (46h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11196909
telemt_connections_bad_total 1264858
telemt_connections_current 1525
telemt_connections_me_current 1525
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 293626
telemt_upstream_connect_attempt_total 89227
telemt_upstream_connect_success_total 88415
telemt_upstream_connect_fail_total 606
telemt_upstream_connect_attempts_per_request{bucket="1"} 89021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 606
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9647
telemt_me_reconnect_success_total 2304
telemt_me_reader_eof_total 2150
telemt_me_idle_close_by_peer_total 2149
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5563852
telemt_me_route_drop_channel_closed_total 353
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8655402
telemt_me_endpoint_quarantine_total 1282
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1248
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 39480
telemt_desync_full_logged_total 12756
telemt_desync_suppressed_total 26724
telemt_desync_frames_bucket_total{bucket="1_2"} 9842
telemt_desync_frames_bucket_total{bucket="3_10"} 14681
telemt_desync_frames_bucket_total{bucket="gt_10"} 14957
telemt_pool_swap_total 175
telemt_pool_force_close_total 4899
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 633
telemt_me_draining_writers_reap_progress_total 56359
telemt_me_writer_removed_unexpected_total 2184
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5976
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52640
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51460
telemt_me_writer_teardown_success_total{mode="normal"} 58616
telemt_me_writer_teardown_noop_total 56364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114980
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.093262
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114980
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 633
telemt_me_refill_failed_total 379
telemt_me_writer_restored_same_endpoint_total 1880
telemt_me_writer_restored_fallback_total 106
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 8661103
telemt_user_connections_current{user="hello"} 1525
telemt_user_octets_from_client{user="hello"} 152730441653 (142.24 GB)
telemt_user_octets_to_client{user="hello"} 3330567057507 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 603
telemt_user_unique_ips_recent_window{user="hello"} 242
```