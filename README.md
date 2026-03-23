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

# Server Metrics 2026-03-23 04:03:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 111451.0 (30h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3798137
telemt_connections_bad_total 371916
telemt_connections_current 1243
telemt_connections_me_current 1243
telemt_handshake_timeouts_total 125788
telemt_upstream_connect_attempt_total 41531
telemt_upstream_connect_success_total 41530
telemt_upstream_connect_attempts_per_request{bucket="1"} 41530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26952
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1446
telemt_me_reconnect_success_total 644
telemt_me_reader_eof_total 661
telemt_me_idle_close_by_peer_total 661
telemt_me_route_drop_no_conn_total 3025911
telemt_me_route_drop_channel_closed_total 1241
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3094647
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 791
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 871
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 13273
telemt_desync_full_logged_total 4219
telemt_desync_suppressed_total 9054
telemt_desync_frames_bucket_total{bucket="1_2"} 3500
telemt_desync_frames_bucket_total{bucket="3_10"} 4866
telemt_desync_frames_bucket_total{bucket="gt_10"} 4907
telemt_pool_swap_total 123
telemt_pool_force_close_total 3741
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 681
telemt_me_draining_writers_reap_progress_total 38043
telemt_me_writer_removed_unexpected_total 638
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2716
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35613
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3685
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34302
telemt_me_writer_teardown_success_total{mode="normal"} 38329
telemt_me_writer_teardown_noop_total 38054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76383
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 381.668962
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76383
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 681
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 578
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 3083490
telemt_user_connections_current{user="hello"} 1243
telemt_user_octets_from_client{user="hello"} 43585430000 (40.59 GB)
telemt_user_octets_to_client{user="hello"} 839469934904 (781.82 GB)
telemt_user_unique_ips_current{user="hello"} 543
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 124816.7 (34h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4078029
telemt_connections_bad_total 380445
telemt_connections_current 619
telemt_connections_me_current 619
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 102831
telemt_upstream_connect_attempt_total 78265
telemt_upstream_connect_success_total 77333
telemt_upstream_connect_fail_total 825
telemt_upstream_connect_attempts_per_request{bucket="1"} 78158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 825
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10637
telemt_me_reconnect_success_total 3775
telemt_me_reader_eof_total 3756
telemt_me_idle_close_by_peer_total 3756
telemt_me_route_drop_no_conn_total 3652699
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3236649
telemt_me_endpoint_quarantine_total 1010
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 51
telemt_me_single_endpoint_outage_exit_total 51
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 983
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
telemt_me_writers_active_current 46
telemt_desync_total 13234
telemt_desync_full_logged_total 7447
telemt_desync_suppressed_total 5787
telemt_desync_frames_bucket_total{bucket="1_2"} 3002
telemt_desync_frames_bucket_total{bucket="3_10"} 5198
telemt_desync_frames_bucket_total{bucket="gt_10"} 5034
telemt_pool_swap_total 118
telemt_pool_force_close_total 3269
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 257
telemt_me_draining_writers_reap_progress_total 52049
telemt_me_writer_removed_unexpected_total 3679
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6620
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49148
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2811
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48780
telemt_me_writer_teardown_success_total{mode="normal"} 55768
telemt_me_writer_teardown_noop_total 52050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107818
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.729652
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107818
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 257
telemt_me_refill_failed_total 270
telemt_me_writer_restored_same_endpoint_total 3341
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 3251123
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 43721988035 (40.72 GB)
telemt_user_octets_to_client{user="hello"} 811691431813 (755.95 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 199676.7 (55h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16505169
telemt_connections_bad_total 1672852
telemt_connections_current 1505
telemt_connections_me_current 1505
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 401875
telemt_upstream_connect_attempt_total 89964
telemt_upstream_connect_success_total 89857
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 89874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44305
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1728
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3102
telemt_me_reconnect_success_total 1643
telemt_me_reader_eof_total 1597
telemt_me_idle_close_by_peer_total 1595
telemt_me_route_drop_no_conn_total 14075450
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13106352
telemt_me_endpoint_quarantine_total 1345
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1510
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
telemt_me_writers_active_current 43
telemt_desync_total 54525
telemt_desync_full_logged_total 17379
telemt_desync_suppressed_total 37146
telemt_desync_frames_bucket_total{bucket="1_2"} 12173
telemt_desync_frames_bucket_total{bucket="3_10"} 21310
telemt_desync_frames_bucket_total{bucket="gt_10"} 21042
telemt_pool_swap_total 216
telemt_pool_force_close_total 6969
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1080
telemt_me_draining_writers_reap_progress_total 68979
telemt_me_writer_removed_unexpected_total 1533
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5780
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64015
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6499
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62010
telemt_me_writer_teardown_success_total{mode="normal"} 69795
telemt_me_writer_teardown_noop_total 69032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138827
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.231666
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138827
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1080
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1425
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 13106321
telemt_user_connections_current{user="hello"} 1505
telemt_user_octets_from_client{user="hello"} 198595237445 (184.96 GB)
telemt_user_octets_to_client{user="hello"} 3544143223391 (3.22 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 643
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 199677.9 (55h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12051021
telemt_connections_bad_total 1273260
telemt_connections_current 872
telemt_connections_me_current 872
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 346793
telemt_upstream_connect_attempt_total 104206
telemt_upstream_connect_success_total 102863
telemt_upstream_connect_fail_total 890
telemt_upstream_connect_attempts_per_request{bucket="1"} 103753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3804
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 890
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4563
telemt_me_reconnect_success_total 1960
telemt_me_reader_eof_total 1827
telemt_me_idle_close_by_peer_total 1827
telemt_me_route_drop_no_conn_total 4577084
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8916650
telemt_me_endpoint_quarantine_total 1363
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1530
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 39233
telemt_desync_full_logged_total 13211
telemt_desync_suppressed_total 26022
telemt_desync_frames_bucket_total{bucket="1_2"} 9723
telemt_desync_frames_bucket_total{bucket="3_10"} 15084
telemt_desync_frames_bucket_total{bucket="gt_10"} 14426
telemt_pool_swap_total 213
telemt_pool_force_close_total 6312
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 67030
telemt_me_writer_removed_unexpected_total 1854
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5871
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62872
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60718
telemt_me_writer_teardown_success_total{mode="normal"} 68743
telemt_me_writer_teardown_noop_total 67055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135798
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.579815
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135798
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 1678
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8854326
telemt_user_connections_current{user="hello"} 872
telemt_user_octets_from_client{user="hello"} 218699886236 (203.68 GB)
telemt_user_octets_to_client{user="hello"} 3996054494531 (3.63 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 383
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 199642.0 (55h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11191462
telemt_connections_bad_total 1006173
telemt_connections_current 826
telemt_connections_me_current 826
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 348321
telemt_upstream_connect_attempt_total 88720
telemt_upstream_connect_success_total 87149
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 87354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5842
telemt_me_reconnect_success_total 2448
telemt_me_reader_eof_total 2194
telemt_me_idle_close_by_peer_total 2193
telemt_me_route_drop_no_conn_total 5355273
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8434839
telemt_me_endpoint_quarantine_total 1406
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1487
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 38419
telemt_desync_full_logged_total 12743
telemt_desync_suppressed_total 25676
telemt_desync_frames_bucket_total{bucket="1_2"} 9703
telemt_desync_frames_bucket_total{bucket="3_10"} 14719
telemt_desync_frames_bucket_total{bucket="gt_10"} 13997
telemt_pool_swap_total 209
telemt_pool_force_close_total 6209
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 753
telemt_me_draining_writers_reap_progress_total 67619
telemt_me_writer_removed_unexpected_total 2340
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6621
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63274
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5638
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61410
telemt_me_writer_teardown_success_total{mode="normal"} 69895
telemt_me_writer_teardown_noop_total 67690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137585
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.905120
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137585
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 753
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2130
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 8426720
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 193399827223 (180.12 GB)
telemt_user_octets_to_client{user="hello"} 3498184239801 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 69922.0 (19h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11457157
telemt_connections_bad_total 674171
telemt_connections_current 1500
telemt_connections_me_current 1500
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 297633
telemt_upstream_connect_attempt_total 63958
telemt_upstream_connect_success_total 60562
telemt_upstream_connect_fail_total 2202
telemt_upstream_connect_attempts_per_request{bucket="1"} 62764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2202
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8237
telemt_me_reconnect_success_total 1435
telemt_me_reader_eof_total 917
telemt_me_idle_close_by_peer_total 916
telemt_me_route_drop_no_conn_total 25325960
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9495892
telemt_me_endpoint_quarantine_total 541
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 561
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
telemt_me_writers_active_current 47
telemt_desync_total 16890
telemt_desync_full_logged_total 4655
telemt_desync_suppressed_total 12235
telemt_desync_frames_bucket_total{bucket="1_2"} 3252
telemt_desync_frames_bucket_total{bucket="3_10"} 6888
telemt_desync_frames_bucket_total{bucket="gt_10"} 6750
telemt_pool_swap_total 72
telemt_pool_force_close_total 2259
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 508
telemt_me_draining_writers_reap_progress_total 23060
telemt_me_writer_removed_unexpected_total 1311
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2991
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21331
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1937
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20801
telemt_me_writer_teardown_success_total{mode="normal"} 24322
telemt_me_writer_teardown_noop_total 23079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47401
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.311636
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47401
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 508
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 927
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 369
telemt_user_connections_total{user="hello"} 9522370
telemt_user_connections_current{user="hello"} 1500
telemt_user_octets_from_client{user="hello"} 89274903466 (83.14 GB)
telemt_user_octets_to_client{user="hello"} 664347353801 (618.72 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 621
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 199648.5 (55h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11156816
telemt_connections_bad_total 984779
telemt_connections_current 1083
telemt_connections_me_current 1083
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 245765
telemt_upstream_connect_attempt_total 117503
telemt_upstream_connect_success_total 116301
telemt_upstream_connect_fail_total 1026
telemt_upstream_connect_attempts_per_request{bucket="1"} 117327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1026
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73346
telemt_me_reconnect_success_total 3198
telemt_me_reader_eof_total 2898
telemt_me_idle_close_by_peer_total 2895
telemt_me_route_drop_no_conn_total 5288773
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8783482
telemt_me_endpoint_quarantine_total 1357
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1517
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
telemt_me_writers_active_current 45
telemt_desync_total 46794
telemt_desync_full_logged_total 16070
telemt_desync_suppressed_total 30724
telemt_desync_frames_bucket_total{bucket="1_2"} 9507
telemt_desync_frames_bucket_total{bucket="3_10"} 17927
telemt_desync_frames_bucket_total{bucket="gt_10"} 19360
telemt_pool_swap_total 205
telemt_pool_force_close_total 5934
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 676
telemt_me_draining_writers_reap_progress_total 71596
telemt_me_writer_removed_unexpected_total 2917
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7167
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67391
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5185
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65662
telemt_me_writer_teardown_success_total{mode="normal"} 74558
telemt_me_writer_teardown_noop_total 71597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 144000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 145419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 145838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 146111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 146145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 146148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 146148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 146151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 146155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 146155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 146155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 146155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 146155
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.334121
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 146155
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 676
telemt_me_refill_failed_total 4316
telemt_me_writer_restored_same_endpoint_total 2695
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8786311
telemt_user_connections_current{user="hello"} 1083
telemt_user_octets_from_client{user="hello"} 197253288541 (183.71 GB)
telemt_user_octets_to_client{user="hello"} 3358830010248 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 136484.8 (37h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11888137
telemt_connections_bad_total 487079
telemt_connections_current 963
telemt_connections_me_current 963
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4806118
telemt_upstream_connect_attempt_total 66400
telemt_upstream_connect_success_total 65925
telemt_upstream_connect_fail_total 462
telemt_upstream_connect_attempts_per_request{bucket="1"} 66387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 236
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 462
telemt_me_reconnect_attempts_total 49228
telemt_me_reconnect_success_total 1927
telemt_me_reader_eof_total 1605
telemt_me_idle_close_by_peer_total 1604
telemt_me_route_drop_no_conn_total 4115692
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5713690
telemt_me_endpoint_quarantine_total 939
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1053
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32098
telemt_desync_full_logged_total 10972
telemt_desync_suppressed_total 21126
telemt_desync_frames_bucket_total{bucket="1_2"} 6428
telemt_desync_frames_bucket_total{bucket="3_10"} 12656
telemt_desync_frames_bucket_total{bucket="gt_10"} 13014
telemt_pool_swap_total 145
telemt_pool_force_close_total 4134
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 388
telemt_me_draining_writers_reap_progress_total 51438
telemt_me_writer_removed_unexpected_total 1648
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4098
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49039
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3690
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47304
telemt_me_writer_teardown_success_total{mode="normal"} 53137
telemt_me_writer_teardown_noop_total 51445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104582
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.765775
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104582
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 388
telemt_me_refill_failed_total 2748
telemt_me_writer_restored_same_endpoint_total 1703
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5705714
telemt_user_connections_current{user="hello"} 963
telemt_user_octets_from_client{user="hello"} 120867967756 (112.57 GB)
telemt_user_octets_to_client{user="hello"} 2222694372750 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 417
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 117455.8 (32h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1611893
telemt_connections_bad_total 37096
telemt_connections_current 735
telemt_connections_me_current 735
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32979
telemt_upstream_connect_attempt_total 55531
telemt_upstream_connect_success_total 55357
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 55503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 815
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2412
telemt_me_reconnect_success_total 976
telemt_me_reader_eof_total 970
telemt_me_idle_close_by_peer_total 970
telemt_me_route_drop_no_conn_total 538376
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1432483
telemt_me_endpoint_quarantine_total 994
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 973
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
telemt_desync_total 10079
telemt_desync_full_logged_total 2837
telemt_desync_suppressed_total 7242
telemt_desync_frames_bucket_total{bucket="1_2"} 3196
telemt_desync_frames_bucket_total{bucket="3_10"} 3802
telemt_desync_frames_bucket_total{bucket="gt_10"} 3081
telemt_pool_swap_total 127
telemt_pool_force_close_total 3197
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 47314
telemt_me_writer_removed_unexpected_total 934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3569
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44722
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3109
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44117
telemt_me_writer_teardown_success_total{mode="normal"} 48291
telemt_me_writer_teardown_noop_total 47318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95609
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.542623
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95609
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 834
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1428162
telemt_user_connections_current{user="hello"} 735
telemt_user_octets_from_client{user="hello"} 26839942301 (25.00 GB)
telemt_user_octets_to_client{user="hello"} 597728247751 (556.68 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 199653.2 (55h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13453141
telemt_connections_bad_total 1627676
telemt_connections_current 1161
telemt_connections_me_current 1161
telemt_handshake_timeouts_total 392949
telemt_upstream_connect_attempt_total 80253
telemt_upstream_connect_success_total 79896
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 80117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40311
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3106
telemt_me_reconnect_success_total 1578
telemt_me_reader_eof_total 1565
telemt_me_idle_close_by_peer_total 1565
telemt_me_route_drop_no_conn_total 4501722
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10136508
telemt_me_endpoint_quarantine_total 1464
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1515
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
telemt_desync_total 42531
telemt_desync_full_logged_total 13889
telemt_desync_suppressed_total 28642
telemt_desync_frames_bucket_total{bucket="1_2"} 10360
telemt_desync_frames_bucket_total{bucket="3_10"} 15622
telemt_desync_frames_bucket_total{bucket="gt_10"} 16549
telemt_pool_swap_total 221
telemt_pool_force_close_total 5791
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 689
telemt_me_draining_writers_reap_progress_total 72648
telemt_me_writer_removed_unexpected_total 1499
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5601
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68602
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5617
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66857
telemt_me_writer_teardown_success_total{mode="normal"} 74203
telemt_me_writer_teardown_noop_total 72650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 144232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 145961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 146344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 146720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 146840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 146853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 146853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 146853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 146853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 146853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 146853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 146853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 146853
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.893492
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 146853
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 689
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1391
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10103110
telemt_user_connections_current{user="hello"} 1161
telemt_user_octets_from_client{user="hello"} 195766846248 (182.32 GB)
telemt_user_octets_to_client{user="hello"} 4496106978112 (4.09 TB)
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 199649.5 (55h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11771162
telemt_connections_bad_total 1380818
telemt_connections_current 909
telemt_connections_me_current 909
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 315651
telemt_upstream_connect_attempt_total 107995
telemt_upstream_connect_success_total 107067
telemt_upstream_connect_fail_total 720
telemt_upstream_connect_attempts_per_request{bucket="1"} 107787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2070
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 720
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10910
telemt_me_reconnect_success_total 2701
telemt_me_reader_eof_total 2507
telemt_me_idle_close_by_peer_total 2506
telemt_me_seq_mismatch_total 104
telemt_me_route_drop_no_conn_total 5670309
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9055376
telemt_me_endpoint_quarantine_total 1640
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1519
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
telemt_me_writers_active_current 44
telemt_desync_total 42174
telemt_desync_full_logged_total 13585
telemt_desync_suppressed_total 28589
telemt_desync_frames_bucket_total{bucket="1_2"} 10959
telemt_desync_frames_bucket_total{bucket="3_10"} 15495
telemt_desync_frames_bucket_total{bucket="gt_10"} 15720
telemt_pool_swap_total 211
telemt_pool_force_close_total 5552
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 72905
telemt_me_writer_removed_unexpected_total 2543
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68555
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5081
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67353
telemt_me_writer_teardown_success_total{mode="normal"} 75545
telemt_me_writer_teardown_noop_total 72910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 145749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 147547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 148086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 148405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 148455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 148455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 148455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 148455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 148455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 148455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 148455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 148455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 148455
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.602956
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 148455
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 426
telemt_me_writer_restored_same_endpoint_total 2158
telemt_me_writer_restored_fallback_total 140
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 9059912
telemt_user_connections_current{user="hello"} 909
telemt_user_octets_from_client{user="hello"} 158360960496 (147.49 GB)
telemt_user_octets_to_client{user="hello"} 3539725743886 (3.22 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 389
telemt_user_unique_ips_recent_window{user="hello"} 130
```